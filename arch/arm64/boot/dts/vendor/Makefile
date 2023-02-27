vendor := $(srctree)/$(src)

ifneq "$(wildcard $(vendor)/qcom)" ""
#OPLUS_DTS_OVERLAY start
	#subdir-y += qcom
#OPLUS_DTS_OVERLAY end
endif
#OPLUS_DTS_OVERLAY start
subdir-y += oplus
#OPLUS_DTS_OVERLAY end
subdir-y += audio-devicetree
subdir-y += camera-devicetree
subdir-y += display-devicetree
subdir-y += mmrm-devicetree
subdir-y += video-devicetree
