Dependencies:
catkin_simple,mpl,planning_ros_utils,cgal_catkin,mav_comm,planning_ros_msgs

Run procedures:
First, run roslaunch polygon_coverage_ros coverage_planner.launch 
then, run ./coverage_service_call.sh
finally, run ./service_publish_all.sh 

TODO: 
1. pass z-axis value and topic names as args
2. integrate the three steps into launch file of full_sim.launch in autonomy_stack


