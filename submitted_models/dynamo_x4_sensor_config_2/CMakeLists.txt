cmake_minimum_required(VERSION 2.8.3)
project(dynamo_x4_sensor_config_2)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch meshes urdf materials
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

install(FILES model.sdf model.config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

