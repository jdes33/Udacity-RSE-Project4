# Udacity-RSE-Project4

## This is my work for the 'Map My World' project
## The project involved using ROS to perform RTAB mapping (real time appearance based mapping)
## Note: I made a new building and modified the robot (from previous projects) for better performance

This is the world I wanted to map:

![Alt text](media/world_view.png?raw=true "world_view")
![Alt text](media/world_top_view.png?raw=true "world_top_view")

This is the result after mapping:
(the yellow spots represent features)
From the bottom left we can see that there were 355 global loop closures detected

![Alt text](media/database_viewer.png?raw=true "database_viewer")


In particular this is the occupancy grid that was generated:

![Alt text](media/occupancy_grid_only.png?raw=true "occupancy_grid_only")

Here are images of the 3D maps that were created.

![Alt text](media/3dmap.png?raw=true "3dmap")
![Alt text](media/3dmap2.png?raw=true "3dmap_view_2")
![Alt text](media/3dmap3.png?raw=true "3dmap_view_3")
