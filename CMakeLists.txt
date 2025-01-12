cmake_minimum_required(VERSION 3.16)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
list(APPEND EXTRA_COMPONENT_DIRS "$ENV{IDF_PATH}/examples/storage/sd_card/sdmmc/components/sd_card")
add_compile_options("-Wno-format")
project(SD_LVGL)
