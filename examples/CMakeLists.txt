# examples executable
set(EXAMPLES_NAME examples)
add_executable(${EXAMPLES_NAME} examples.cpp)
target_link_libraries(${EXAMPLES_NAME}
    ${SPEED_RADAR_LIB_NAME}
)
