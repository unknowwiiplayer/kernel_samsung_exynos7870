<<<<<<< HEAD
dtb-$(CONFIG_MACH_EXYNOS7870_GTANOTEXLWIFI_KOR_OPEN) := \
	exynos7870-gtanotexlwifi_kor_open_00.dtb \
	exynos7870-gtanotexlwifi_kor_open_02.dtb

targets += dtbs

DTB_NAMES := $(subst $\",,$(CONFIG_BUILD_ARM64_APPENDED_DTB_IMAGE_NAMES))
ifneq ($(DTB_NAMES),)
DTB_LIST := $(addsuffix .dtb,$(DTB_NAMES))
else
DTB_LIST := $(dtb-y)
endif
targets += $(DTB_LIST)
dtbs: $(addprefix $(obj)/, $(DTB_LIST))
clean-files := dts/*.dtb *.dtb
=======
dtb-y += exynos7870-gtanotexlwifi_kor_open_00.dtb
dtb-y += exynos7870-gtanotexlwifi_kor_open_02.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
>>>>>>> d3008ee67f4ddaa3c221bd2e34945109f52b52bc
