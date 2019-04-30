

add_library(7z SHARED
        C/7zBuf2.c
        C/7zCrc.c
        C/7zCrcOpt.c
        C/7zStream.c
        C/Alloc.c
        C/Bra.c
        C/CpuArch.c
        C/Delta.c
        C/LzFind.c
        C/Lzma2Dec.c
        C/Lzma2Enc.c
        C/Lzma86Dec.c
        C/Lzma86Enc.c
        C/LzmaDec.c
        C/LzmaEnc.c
        C/MtCoder.c
        C/Sha256.c
        C/Threads.c
        C/Xz.c
        C/XzCrc64.c
        C/XzDec.c
        C/XzEnc.c
        C/XzIn.c
        )


target_include_directories(7z PRIVATE
        ${CMAKE_CURRENT_SOURCE_DIR}
        ${CMAKE_CURRENT_SOURCE_DIR}/C
        )

target_link_libraries(7z

        )