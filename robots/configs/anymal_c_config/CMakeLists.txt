cmake_minimum_required(VERSION 2.8.3)
project(anymal_c_config)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY launch config maps worlds
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
