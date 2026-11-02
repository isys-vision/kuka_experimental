cmake_minimum_required(VERSION 3.22.0)
project(kuka_resources)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
