#
# Makefile for sensor drivers
#

obj-$(CONFIG_VIDEO_ATOMISP_OV5693)     += ov5693/
obj-$(CONFIG_VIDEO_ATOMISP_MT9M114)    += atomisp-mt9m114.o
obj-$(CONFIG_VIDEO_ATOMISP_GC2235)     += atomisp-gc2235.o
obj-$(CONFIG_VIDEO_ATOMISP_OV2722)     += atomisp-ov2722.o
obj-$(CONFIG_VIDEO_ATOMISP_OV2680)     += atomisp-ov2680.o
obj-$(CONFIG_VIDEO_ATOMISP_GC0310)     += atomisp-gc0310.o

obj-$(CONFIG_VIDEO_ATOMISP_MSRLIST_HELPER) += atomisp-libmsrlisthelper.o

# Makefile for flash drivers
#

obj-$(CONFIG_VIDEO_ATOMISP_LM3554) += atomisp-lm3554.o

# HACK! While this driver is in bad shape, don't enable several warnings
#       that would be otherwise enabled with W=1
ccflags-y += $(call cc-disable-warning, unused-but-set-variable)
ccflags-y += $(call cc-disable-warning, unused-const-variable)
ccflags-y += $(call cc-disable-warning, missing-prototypes)
ccflags-y += $(call cc-disable-warning, missing-declarations)
