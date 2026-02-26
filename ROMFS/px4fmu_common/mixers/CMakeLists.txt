#
# This CMakeLists.txt file lists all custom mixer files to be included 
# in the final PX4 ROMFS image (rootfs in SITL).
#
# List the mixer files without the .main.mix extension.

px4_add_romfs_files(
    coax16
)

# You can use the generic 'list(APPEND INIT_MIXER_FILES ...)' syntax,
# but the 'px4_add_romfs_files' macro is the standard method used
# throughout PX4's build system for file inclusion.
