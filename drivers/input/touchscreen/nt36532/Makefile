#
# Makefile for the Novatek NT36xxx touchscreen driver.
#

# Each configuration option enables a list of files.

obj-$(CONFIG_TOUCHSCREEN_NT36532_HOSTDL_SPI) += nt36532_touch.o
nt36532_touch-y := nt36xxx.o \
	nt36xxx_fw_update.o \
	nt36xxx_ext_proc.o \
	drm_notifier_mi.o