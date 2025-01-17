cmake_minimum_required(VERSION 3.28)
project(ASCII_IMAGE_CONVERTER)

add_compile_options(-Wall -Wextra -Werror)

add_executable(aic src/main.c)
target_link_libraries(aic m)