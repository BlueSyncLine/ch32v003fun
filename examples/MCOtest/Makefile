all : flash

TARGET:=MCOtest

CFLAGS+=-DTINYVECTOR -DSTDOUT_UART

include ../../ch32v003fun/ch32v003fun.mk

flash : cv_flash
clean : cv_clean

