cmake_minimum_required(VERSION 3.5)

project(App LANGUAGES C)

add_executable(App App.c)

target_include_directories(App PRIVATE ../RTE)
target_link_libraries(App PRIVATE Rte)

