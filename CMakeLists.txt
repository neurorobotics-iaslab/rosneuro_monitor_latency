cmake_minimum_required(VERSION 3.0)
project(rosneuro_monitor_latency)

find_package(catkin REQUIRED COMPONENTS 
			 message_generation
			 rospy
			 std_msgs
			 rosneuro_msgs
			 )

catkin_package(
  CATKIN_DEPENDS
  	message_runtime
)

catkin_python_setup()



