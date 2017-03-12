Haiku DRM
=======================
This fork is to support the GSoC 2017 project for implementing graphics hardware acceleration. This repo *IS NOT CURRENTLY IN A BUILDABLE STATE* and will not be until the compatibility layer is completed.

For more information about Haiku, please visit http://www.haiku-os.org

Thanks for visiting!

DRM sources live in:
    haiku_drm/src/add-ons/kernel/drivers/graphics/drm
DRM headers live in:
    haiku_drm/headers/private/graphics/drm
Compatibility layer(s) live in:
    haiku_drm/src/libs/compat/dragonfly_drm
    haiku_drm/src/libs/compat/linux_drm

The two compatibility layers are in case we choose to utilize DragonflyBSD's compatibility layer (which would require heavy modification) or develop our own. That decision is TBD.
