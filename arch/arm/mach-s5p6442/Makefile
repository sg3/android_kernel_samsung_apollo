# arch/arm/mach-s5p6442/Makefile
#
# Copyright (c) 2009-2010 Samsung Electronics Co., Ltd.
# 		http://www.samsung.com
#
# Licensed under GPLv2
#
# Originally for S5P64x0 and adapted to S5P6442 by Mark Kennard
#

obj-y				:=
obj-m				:=
obj-n				:=
obj-				:=

# Core support for S5P6442 system

obj-$(CONFIG_ARCH_S5P6442)	+= cpu.o init.o clock.o dma.o gpiolib.o
obj-$(CONFIG_ARCH_S5P6442)	+= setup-i2c0.o
obj-$(CONFIG_CPU_S5P6442)	+= clock-s5p6442.o

# machine support

obj-$(CONFIG_MACH_APOLLO)	+= mach-apollo.o

# device support

obj-y				+= dev-audio.o
obj-$(CONFIG_S3C64XX_DEV_SPI)	+= dev-spi.o

obj-$(CONFIG_S5P6442_SETUP_I2C1)	+= setup-i2c1.o
