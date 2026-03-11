# TidyBot3D-Rearrange3D-lab2_kitchen-o2-put_the_can_on_the_left_and_the_boxed_drink_on_the_right_side_of_the_bowl

## Usage
```python
import kinder
env = kinder.make("kinder/TidyBot3D-Rearrange3D-lab2_kitchen-o2-put_the_can_on_the_left_and_the_boxed_drink_on_the_right_side_of_the_bowl-v0")
```

## Description
This variant uses the 'lab2_kitchen' scene type with 2 objects.

## Initial State Distribution
![initial state GIF](../../assets/initial_state_gifs/variants/TidyBot3D-Rearrange3D-lab2_kitchen-o2-put_the_can_on_the_left_and_the_boxed_drink_on_the_right_side_of_the_bowl.gif)

## Random Action Behavior
![random action GIF](../../assets/random_action_gifs/variants/TidyBot3D-Rearrange3D-lab2_kitchen-o2-put_the_can_on_the_left_and_the_boxed_drink_on_the_right_side_of_the_bowl.gif)

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
| 32 | can_0 | x |
| 33 | can_0 | y |
| 34 | can_0 | z |
| 35 | can_0 | qw |
| 36 | can_0 | qx |
| 37 | can_0 | qy |
| 38 | can_0 | qz |
| 39 | can_0 | vx |
| 40 | can_0 | vy |
| 41 | can_0 | vz |
| 42 | can_0 | wx |
| 43 | can_0 | wy |
| 44 | can_0 | wz |
| 45 | can_0 | bb_x |
| 46 | can_0 | bb_y |
| 47 | can_0 | bb_z |
| 48 | kitchen_cooking_area | x |
| 49 | kitchen_cooking_area | y |
| 50 | kitchen_cooking_area | z |
| 51 | kitchen_cooking_area | qw |
| 52 | kitchen_cooking_area | qx |
| 53 | kitchen_cooking_area | qy |
| 54 | kitchen_cooking_area | qz |
| 55 | kitchen_cooking_area_upper | x |
| 56 | kitchen_cooking_area_upper | y |
| 57 | kitchen_cooking_area_upper | z |
| 58 | kitchen_cooking_area_upper | qw |
| 59 | kitchen_cooking_area_upper | qx |
| 60 | kitchen_cooking_area_upper | qy |
| 61 | kitchen_cooking_area_upper | qz |
| 62 | kitchen_island | x |
| 63 | kitchen_island | y |
| 64 | kitchen_island | z |
| 65 | kitchen_island | qw |
| 66 | kitchen_island | qx |
| 67 | kitchen_island | qy |
| 68 | kitchen_island | qz |
| 69 | kitchen_left_corner | x |
| 70 | kitchen_left_corner | y |
| 71 | kitchen_left_corner | z |
| 72 | kitchen_left_corner | qw |
| 73 | kitchen_left_corner | qx |
| 74 | kitchen_left_corner | qy |
| 75 | kitchen_left_corner | qz |
| 76 | kitchen_left_side | x |
| 77 | kitchen_left_side | y |
| 78 | kitchen_left_side | z |
| 79 | kitchen_left_side | qw |
| 80 | kitchen_left_side | qx |
| 81 | kitchen_left_side | qy |
| 82 | kitchen_left_side | qz |
| 83 | robot | pos_base_x |
| 84 | robot | pos_base_y |
| 85 | robot | pos_base_rot |
| 86 | robot | pos_arm_joint1 |
| 87 | robot | pos_arm_joint2 |
| 88 | robot | pos_arm_joint3 |
| 89 | robot | pos_arm_joint4 |
| 90 | robot | pos_arm_joint5 |
| 91 | robot | pos_arm_joint6 |
| 92 | robot | pos_arm_joint7 |
| 93 | robot | pos_gripper |
| 94 | robot | vel_base_x |
| 95 | robot | vel_base_y |
| 96 | robot | vel_base_rot |
| 97 | robot | vel_arm_joint1 |
| 98 | robot | vel_arm_joint2 |
| 99 | robot | vel_arm_joint3 |
| 100 | robot | vel_arm_joint4 |
| 101 | robot | vel_arm_joint5 |
| 102 | robot | vel_arm_joint6 |
| 103 | robot | vel_arm_joint7 |
| 104 | robot | vel_gripper |
