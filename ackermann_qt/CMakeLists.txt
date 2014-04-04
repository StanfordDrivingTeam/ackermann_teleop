cmake_minimum_required(VERSION 2.8.3)
project(ackermann_qt)

find_package(catkin REQUIRED COMPONENTS dynamic_reconfigure)

generate_dynamic_reconfigure_options(cfg/QTeleop.cfg)

catkin_package(CATKIN_DEPENDS dynamic_reconfigure)

