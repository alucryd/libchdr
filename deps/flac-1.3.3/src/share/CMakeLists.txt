add_subdirectory("replaygain_analysis")
add_subdirectory("replaygain_synthesis")
add_subdirectory("getopt")
add_subdirectory("utf8")
if(WIN32)
    add_subdirectory("win_utf8_io")
endif()
add_subdirectory("grabbag")
