ifeq ($(CONFIG_VITHAR_HWVER_R0P0),y)
obj-y			+= drm/ vga/ stub/ ion/ vithar/
else
obj-y			+= drm/ vga/ stub/ ion/ vithar_rev0/
endif

ifeq ($(CONFIG_MALI400),y)
ifeq ($(CONFIG_MALI_VER_R3P2),y)
obj-y           += mali400/r3p2/mali/
obj-y           += mali400/r3p2/ump/
else
ifeq ($(CONFIG_MALI_VER_R4P0),y)
obj-y           += mali400/r4p0/mali/
obj-y           += mali400/r4p0/ump/
endif
endif
endif
