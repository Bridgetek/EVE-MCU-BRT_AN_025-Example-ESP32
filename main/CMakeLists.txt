set( CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DPROGMEM=")
set(COMPONENT_SRCS "main.c" "../example/eve_calibrate.c" "../example/eve_example.c" "../example/eve_fonts.c" "../example/eve_images.c" "../example/eve_helper.c")
set(COMPONENT_ADD_INCLUDEDIRS "../lib/eve/include" "../example")
register_component()