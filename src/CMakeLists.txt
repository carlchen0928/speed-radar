set(SPEED_RADAR_LIB_NAME speedradar)

add_library(${SPEED_RADAR_LIB_NAME}
    speed_radar.cpp
)

target_link_libraries(${SPEED_RADAR_LIB_NAME})
