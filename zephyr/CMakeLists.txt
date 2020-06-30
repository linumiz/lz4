if(CONFIG_LZ4)

zephyr_include_directories(../lib)
zephyr_library()

zephyr_library_sources(
	../lib/lz4.c
)

endif()
