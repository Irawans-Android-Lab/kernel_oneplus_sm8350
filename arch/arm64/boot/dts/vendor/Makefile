vendor := $(srctree)/$(src)

ifneq ($(VENDOR_EDIT),yes)
subdir-y += qcom
endif
ifeq ($(BRAND_SHOW_FLAG),realme)
subdir-y += oplus/cupid
subdir-y += oplus/lunaa
subdir-y += oplus/porsche
else
subdir-y += oplus/lemonadev
subdir-y += oplus/martini
endif
