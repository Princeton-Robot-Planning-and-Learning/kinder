# TidyBot3D-Rearrange3D-lab2_kitchen-o1-put_the_boxed_drink_behind_the_bowl

## Usage
```python
import kinder
env = kinder.make("kinder/TidyBot3D-Rearrange3D-lab2_kitchen-o1-put_the_boxed_drink_behind_the_bowl-v0")
```

## Description
This variant uses the 'lab2_kitchen' scene type with 1 object.

## Initial State Distribution
![initial state GIF](../../assets/initial_state_gifs/variants/TidyBot3D-Rearrange3D-lab2_kitchen-o1-put_the_boxed_drink_behind_the_bowl.gif)

## Random Action Behavior
![random action GIF](../../assets/random_action_gifs/variants/TidyBot3D-Rearrange3D-lab2_kitchen-o1-put_the_boxed_drink_behind_the_bowl.gif)

**Random Action Stats**: Total Reward: -0.25, Success: No, Steps: 25

## Example Demonstration
*(No demonstration GIFs available)*

## Observation Space
The entries of an array in this Box space correspond to the following object features:
| **Index** | **Object** | **Feature** |
| --- | --- | --- |
| 0 | bowl_0 | x |
| 1 | bowl_0 | y |
| 2 | bowl_0 | z |
| 3 | bowl_0 | qw |
| 4 | bowl_0 | qx |
| 5 | bowl_0 | qy |
| 6 | bowl_0 | qz |
| 7 | bowl_0 | vx |
| 8 | bowl_0 | vy |
| 9 | bowl_0 | vz |
| 10 | bowl_0 | wx |
| 11 | bowl_0 | wy |
| 12 | bowl_0 | wz |
| 13 | bowl_0 | bb_x |
| 14 | bowl_0 | bb_y |
| 15 | bowl_0 | bb_z |
| 16 | boxed_drink_0 | x |
| 17 | boxed_drink_0 | y |
| 18 | boxed_drink_0 | z |
| 19 | boxed_drink_0 | qw |
| 20 | boxed_drink_0 | qx |
| 21 | boxed_drink_0 | qy |
| 22 | boxed_drink_0 | qz |
| 23 | boxed_drink_0 | vx |
| 24 | boxed_drink_0 | vy |
| 25 | boxed_drink_0 | vz |
| 26 | boxed_drink_0 | wx |
| 27 | boxed_drink_0 | wy |
| 28 | boxed_drink_0 | wz |
| 29 | boxed_drink_0 | bb_x |
| 30 | boxed_drink_0 | bb_y |
| 31 | boxed_drink_0 | bb_z |
| 32 | kitchen_cooking_area | x |
| 33 | kitchen_cooking_area | y |
| 34 | kitchen_cooking_area | z |
| 35 | kitchen_cooking_area | qw |
| 36 | kitchen_cooking_area | qx |
| 37 | kitchen_cooking_area | qy |
| 38 | kitchen_cooking_area | qz |
| 39 | kitchen_cooking_area_upper | x |
| 40 | kitchen_cooking_area_upper | y |
| 41 | kitchen_cooking_area_upper | z |
| 42 | kitchen_cooking_area_upper | qw |
| 43 | kitchen_cooking_area_upper | qx |
| 44 | kitchen_cooking_area_upper | qy |
| 45 | kitchen_cooking_area_upper | qz |
| 46 | kitchen_island | x |
| 47 | kitchen_island | y |
| 48 | kitchen_island | z |
| 49 | kitchen_island | qw |
| 50 | kitchen_island | qx |
| 51 | kitchen_island | qy |
| 52 | kitchen_island | qz |
| 53 | kitchen_left_corner | x |
| 54 | kitchen_left_corner | y |
| 55 | kitchen_left_corner | z |
| 56 | kitchen_left_corner | qw |
| 57 | kitchen_left_corner | qx |
| 58 | kitchen_left_corner | qy |
| 59 | kitchen_left_corner | qz |
| 60 | kitchen_left_side | x |
| 61 | kitchen_left_side | y |
| 62 | kitchen_left_side | z |
| 63 | kitchen_left_side | qw |
| 64 | kitchen_left_side | qx |
| 65 | kitchen_left_side | qy |
| 66 | kitchen_left_side | qz |
| 67 | robot | pos_base_x |
| 68 | robot | pos_base_y |
| 69 | robot | pos_base_rot |
| 70 | robot | pos_arm_joint1 |
| 71 | robot | pos_arm_joint2 |
| 72 | robot | pos_arm_joint3 |
| 73 | robot | pos_arm_joint4 |
| 74 | robot | pos_arm_joint5 |
| 75 | robot | pos_arm_joint6 |
| 76 | robot | pos_arm_joint7 |
| 77 | robot | pos_gripper |
| 78 | robot | vel_base_x |
| 79 | robot | vel_base_y |
| 80 | robot | vel_base_rot |
| 81 | robot | vel_arm_joint1 |
| 82 | robot | vel_arm_joint2 |
| 83 | robot | vel_arm_joint3 |
| 84 | robot | vel_arm_joint4 |
| 85 | robot | vel_arm_joint5 |
| 86 | robot | vel_arm_joint6 |
| 87 | robot | vel_arm_joint7 |
| 88 | robot | vel_gripper |
