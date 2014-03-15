AM_CFLAGS = --pedantic -Wall -std=gnu99 -Os -I libmicro/include -I include -Wformat -Wformat-security -Werror=format-security -Wextra

bin_PROGRAMS = cand
cand_SOURCES = src/main.c src/opendevice.c libmicro/uart/uart-host.c libmicro/can/can-uart.c libmicro/can/can-encap.c libmicro/can/can-tcp.c libmicro/utils/debug.c libmicro/utils/crc16.c
