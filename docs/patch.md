# Дополнения

## Изменения в gcc

## 1

В gcc на стенде Каракатицы вместо ```gcc-riscv64-unknown-elf``` установлен ```riscv64-linux-gnu-gcc```, которому нужны немного другие флаги для сборки:

```
CROSS_COMPILE=riscv64-linux-gnu-
...
COMMON := -march=rv32imac -mabi=ilp32 -mcmodel=medany -static -gdwarf-2 -fno-plt -fno-pic
ASMFLAGS := $(COMMON)
LDFLAGS := $(COMMON) -Wl,--build-id=none -nostdlib -T lib/gd32vf103cbt6.ld
```

## 2 (23.03.2023)

В gcc version 12.1.1 (на ALT Linux на сервере Каракатицы) после обновления надо по-другому указывать архитектуру: не ```-march=rv32imac```, а ```-march=rv32imac_zicsr_zifencei```