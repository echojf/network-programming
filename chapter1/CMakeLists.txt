aux_source_directory(. DIR_CHAPTER1_SRCS)
add_library(chapter1 ${DIR_CHAPTER1_SRCS})

add_executable(daytimetcpcli daytimetcpcli.c)