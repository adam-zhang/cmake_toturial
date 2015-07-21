set(sources hello.cpp)
add_library(libHello SHARED ${sources})
set_target_properties(libHello PROPERTIES OUTPUT_NAME "Hello")
