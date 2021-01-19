# sac-competition
Clone this repository <br>

Add marker10 and sampleQR to models in .gazebo <br>

## For Sample Arena:

Change path in line `7` of `sample_arena.launch`  
   
   ```
	<arg name="world" default="/home/neha_kurian/catkin_ws/src/arena_with_qr/world/sample_arena.world" />
   ```

Change path in line `105` and `127` in `sample_arena.world`

   ```
	<uri>/home/neha_kurian/catkin_ws/src/sample_arena_urdf/meshes/arena_samplenew.dae</uri>
   ```

Open terminal from your <workspace> and do
   
   ```
   catkin_make
   source devel/setup.bash
   roslaunch arena_with_qr sample_arena.launch

   ```

## For Final Arena:

Change path in line `7` of `final_arena.launch `
   
   ```
	  <arg name="world" default="/home/neha_kurian/catkin_ws/src/arena_with_qr/world/final_arena.world" />
   ```

Change path in line `293` and `315` in `final_arena.world`

   ```
	<uri>/home/neha_kurian/catkin_ws/src/final_arena_urdf/meshes/final_arena.dae</uri>
   ```

Open terminal from your <workspace> and do
   
   ```
   catkin_make
   source devel/setup.bash
   roslaunch arena_with_qr final_arena.launch
   ```
