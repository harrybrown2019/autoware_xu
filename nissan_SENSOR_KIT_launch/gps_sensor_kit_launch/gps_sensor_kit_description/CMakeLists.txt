cmake_minimum_required(VERSION 3.5)
project(gps_sensor_kit_description)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY config urdf
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
