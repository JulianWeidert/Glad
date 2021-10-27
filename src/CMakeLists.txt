add_library(glad "gl.c" "${GLAD_SOURCE_DIR}/include/glad/gl.h")

target_include_directories(glad PUBLIC "${GLAD_SOURCE_DIR}/include")