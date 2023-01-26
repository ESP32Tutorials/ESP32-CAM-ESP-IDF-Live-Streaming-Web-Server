set(srcs "main.c"
	     "connect_wifi.c")
idf_component_register(SRCS ${srcs}
                    INCLUDE_DIRS ".")
