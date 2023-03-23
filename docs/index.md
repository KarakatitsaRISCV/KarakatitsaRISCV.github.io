# RISC-V на примере микроконтроллера GD32VF103

Экспериментальный курс по практике программирования RISC-V на реальном железе (микроконтроллере GD32VF103)

## Оглавление

[**Внимание, патчи**](patch.md)

[Все исходники, репозиторий](https://github.com/KarakatitsaRISCV/riscv-asm)

[Плейлист на Youtube](https://www.youtube.com/watch?v=ArJey3KuUyA&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q)

| Текстовая версия | Видеоверсия | Исходный код |
|------------------|-------------|--------------|
| [1. Введение](1.intro.md) | [Youtube](https://www.youtube.com/watch?v=ArJey3KuUyA&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q) | []() |
| [2. Мигалка светодиодом](2.blink.md) | [Youtube](https://www.youtube.com/watch?v=7UrrxNjqqf8&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=2) | [исходник](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/1.blink) |
| [3. Битовая магия](3.bitmagic.md) | [Youtube](https://www.youtube.com/watch?v=uTbyINbwNvs&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=3) | []() |
| [4. UART](4.uart.md) | [Youtube](https://www.youtube.com/watch?v=uZaMwdrY9Eo&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=4) | [исходник](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/2.uart) |
| [5. Организация памяти](5.memory.md) | [Youtube](https://www.youtube.com/watch?v=ECqfoAc8lec&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=5) | [исходник](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/3.memory) |
| [6. Прерывания](6.interrupts.md) | [Youtube](https://www.youtube.com/watch?v=OYTF6iVvZTo&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=6) | [исходник](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/4.interrupt) |
| [7. Переход на Си](7.C.md) | [Youtube](https://www.youtube.com/watch?v=DDSGIknu4Ak&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=7) | [исходник](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/5.C) |
| [8. Матричная организация периферии](8.matrix.md) | [Youtube](https://www.youtube.com/watch?v=HP7zUQoAAEQ&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=8) | [клавиатура](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/6.matrix_kbd) [дисплей](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/7.matrix_led) |
| [9. Таймеры и тактирование](9.timers.md) | [Youtube](https://www.youtube.com/watch?v=8WR9gepvWAE&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=9) | [исходник](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/8.timer) |
| [10. DMA](10.DMA.md) | [Youtube](https://www.youtube.com/watch?v=myDKs9CTM6k&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=10) | [исходник](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/9.DMA) |
| [11. Многозадачность](11.multitask.md) | [Youtube](https://www.youtube.com/watch?v=Pb8y5IBaTto&list=PLc7FYD_FgfqcgaWyrxhSr8cy2q23xCY3Q&index=11) | [конечный автомат](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/10.Multitask_finite_state_machine); [кооперативная](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/11.Multitack_Cooperative); [вытесняющая](https://github.com/KarakatitsaRISCV/riscv-asm/tree/main/12.Multitask_preemptive) |

Что такое [Каракатица](Karakatitsa.md)

Как подключиться: [Linux](Remote_lin.md) / [Windows + IDE](Remote_win.md)

Появился чат для обсуждения: [https://t.me/KarakatitsaRISCV](https://t.me/KarakatitsaRISCV)