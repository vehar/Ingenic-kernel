
obj-y += vehicle-misc.o vehicle-pm.o vehicle-lcd.o

obj-$(CONFIG_I2C)		+= vehicle-i2c.o
obj-$(CONFIG_MFD_ACT8600)	+= vehicle-regulator.o
obj-$(CONFIG_MMC_JZ4780)	+= vehicle-mmc.o
obj-$(CONFIG_JZ4780_INTERNAL_CODEC) += vehicle-sound.o

ifeq ($(CONFIG_BOARD_TROOPER), y)
EXTRA_CFLAGS+=-DCONFIG_BOARD_VEHICLE_V_1_1
endif
