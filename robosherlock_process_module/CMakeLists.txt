cmake_minimum_required(VERSION 2.8.3)
project(robosherlock_process_module)

find_package(catkin REQUIRED COMPONENTS
  roslisp
  alexandria
  cram_process_modules
  cram_designators
  cram_plan_occasions_events
  cram_pr2_designators
  cl_transforms
  cram_semantic_map_costmap
  actionlib
  cram_designators
  cram_uima
  cram_moveit)

catkin_package()
include_directories(
  ${catkin_INCLUDE_DIRS}
)
