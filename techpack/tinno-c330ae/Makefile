ifeq ($(CONFIG_MACH_TINNO_C330AE),y)
obj-$(CONFIG_INPUT_TOUCHSCREEN) += ft8006p/
else
ccflags-y := -Wno-unused-function
obj-y := stub.o
endif
