ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_RACER_DTB) += \
                racer/lito-racer_01.dtbo \
                racer/lito-racer_02.dtbo \
                racer/lito-racer_03.dtbo

        dtbo-$(CONFIG_BURTON_DTB) += \
                burton/kona-burton_00.dtbo \
                burton/kona-burton_01.dtbo \
                burton/kona-burton_02.dtbo \
                burton/kona-burton_03.dtbo \
                burton/kona-burton_04.dtbo \
                burton/kona-burton_05.dtbo
endif

always		:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
