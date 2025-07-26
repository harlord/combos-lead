# combos-lead/CMakeLists.txt
zephyr_library()                               # creates library named after directory
zephyr_library_sources(
  src/combo.c
)
zephyr_include_directories(
  include
)