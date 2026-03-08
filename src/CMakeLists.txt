project(cpptest_main)

add_subdirectory(map1)
add_subdirectory(map2)

add_executable(${PROJECT_NAME} main.cpp)

target_include_directories(${PROJECT_NAME}
PUBLIC
${Map1_Dir}
)

target_link_libraries(${PROJECT_NAME}
PUBLIC
map1
)
