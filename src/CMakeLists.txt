remake_find_package(libusb-1.0 CONFIG)
remake_find_package(libudev CONFIG)
remake_find_package(libpng CONFIG)

remake_include(
  lib
  ${LIBUSB_1_0_INCLUDE_DIRS}
  ${LIBUDEV_INCLUDE_DIRS}
  ${LIBPNG_INCLUDE_DIRS}
)

remake_add_directories(lib bin)
