project(map1)

add_library(${PROJECT_NAME}
SHARED
m1.cpp
)

target_include_directories(${PROJECT_NAME}
PUBLIC
${Map2_Dir}
)

target_link_libraries(${PROJECT_NAME}
PUBLIC
map2
)