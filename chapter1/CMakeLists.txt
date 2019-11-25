aux_source_directory(. DIR_CHAPTER1_SRCS)
add_library(chapter1 ${DIR_CHAPTER1_SRCS})

add_executable(daytimetcpcli daytimetcpcli.c)
add_executable(daytimetcpsrv daytimetcpsrv.c)

target_link_libraries(daytimetcpsrv PUBLIC unp)

