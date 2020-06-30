project(handsfree)

cmake_minimum_required(VERSION 2.8.3)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(handsfree_2dnav)
add_subdirectory(handsfree_ar_tags)
add_subdirectory(handsfree_bringup)
add_subdirectory(handsfree_camera)
add_subdirectory(handsfree_controller)
add_subdirectory(handsfree_dataset)
add_subdirectory(handsfree_gazebo)
add_subdirectory(handsfree_hw)
add_subdirectory(handsfree_msgs)
add_subdirectory(handsfree_smach)
add_subdirectory(handsfree_stage)
add_subdirectory(handsfree_vision)
add_subdirectory(rplidar_ros)