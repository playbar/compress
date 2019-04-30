cmake_minimum_required(VERSION 3.4.1)

aux_source_directory(. DIR_JNI_SOURCE)
include_directories(./ ./lzma1805/C)
add_subdirectory(./lzma1805/C)

add_executable(7zip
        lzmaSdkExecutor.c
        )
target_link_libraries(7zip lzma1805)
