cmake_minimum_required(VERSION 3.18)
project(ImFileDialog)

# ##############################################################################
# Build Files
# ##############################################################################
aux_source_directory(. SRC_LIST)

# ##############################################################################
# Targets
# ##############################################################################
add_library(ImFileDialog STATIC ${SRC_LIST})
target_include_directories(ImFileDialog PUBLIC .)
