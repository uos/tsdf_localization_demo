cmake_minimum_required(VERSION 3.0.2)
project(tsdf_localization_demo)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY
    launch/
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/launch
)

install(DIRECTORY
    worlds/
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/worlds
)
