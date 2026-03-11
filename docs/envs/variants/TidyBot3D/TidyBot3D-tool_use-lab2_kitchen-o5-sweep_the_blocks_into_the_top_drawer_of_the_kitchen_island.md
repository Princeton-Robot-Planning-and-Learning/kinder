# SweepIntoDrawer3D-lab2_kitchen-o5-sweep_the_blocks_into_the_top_drawer_of_the_kitchen_island

## Usage
```python
import kinder
env = kinder.make("kinder/SweepIntoDrawer3D-lab2_kitchen-o5-sweep_the_blocks_into_the_top_drawer_of_the_kitchen_island-v0")
```

## Description
This variant uses the 'ground' scene type with 3 objects.

## Initial State Distribution
![initial state GIF](../../assets/initial_state_gifs/variants/SweepIntoDrawer3D-lab2_kitchen-o5-sweep_the_blocks_into_the_top_drawer_of_the_kitchen_island.gif)

## Random Action Behavior
![random action GIF](../../assets/random_action_gifs/variants/SweepIntoDrawer3D-lab2_kitchen-o5-sweep_the_blocks_into_the_top_drawer_of_the_kitchen_island.gif)

**Random Action Stats**: Total Reward: -0.25, Success: No, Steps: 25

## Example Demonstration
*(No demonstration GIFs available)*

## Observation Space
The entries of an array in this Box space correspond to the following object features:
| **Index** | **Object** | **Feature** |
| --- | --- | --- |
| 0 | cube_0 | x |
| 1 | cube_0 | y |
| 2 | cube_0 | z |
| 3 | cube_0 | qw |
| 4 | cube_0 | qx |
| 5 | cube_0 | qy |
| 6 | cube_0 | qz |
| 7 | cube_0 | vx |
| 8 | cube_0 | vy |
| 9 | cube_0 | vz |
| 10 | cube_0 | wx |
| 11 | cube_0 | wy |
| 12 | cube_0 | wz |
| 13 | cube_0 | bb_x |
| 14 | cube_0 | bb_y |
| 15 | cube_0 | bb_z |
| 16 | cube_1 | x |
| 17 | cube_1 | y |
| 18 | cube_1 | z |
| 19 | cube_1 | qw |
| 20 | cube_1 | qx |
| 21 | cube_1 | qy |
| 22 | cube_1 | qz |
| 23 | cube_1 | vx |
| 24 | cube_1 | vy |
| 25 | cube_1 | vz |
| 26 | cube_1 | wx |
| 27 | cube_1 | wy |
| 28 | cube_1 | wz |
| 29 | cube_1 | bb_x |
| 30 | cube_1 | bb_y |
| 31 | cube_1 | bb_z |
| 32 | cube_2 | x |
| 33 | cube_2 | y |
| 34 | cube_2 | z |
| 35 | cube_2 | qw |
| 36 | cube_2 | qx |
| 37 | cube_2 | qy |
| 38 | cube_2 | qz |
| 39 | cube_2 | vx |
| 40 | cube_2 | vy |
| 41 | cube_2 | vz |
| 42 | cube_2 | wx |
| 43 | cube_2 | wy |
| 44 | cube_2 | wz |
| 45 | cube_2 | bb_x |
| 46 | cube_2 | bb_y |
| 47 | cube_2 | bb_z |
| 48 | cube_3 | x |
| 49 | cube_3 | y |
| 50 | cube_3 | z |
| 51 | cube_3 | qw |
| 52 | cube_3 | qx |
| 53 | cube_3 | qy |
| 54 | cube_3 | qz |
| 55 | cube_3 | vx |
| 56 | cube_3 | vy |
| 57 | cube_3 | vz |
| 58 | cube_3 | wx |
| 59 | cube_3 | wy |
| 60 | cube_3 | wz |
| 61 | cube_3 | bb_x |
| 62 | cube_3 | bb_y |
| 63 | cube_3 | bb_z |
| 64 | cube_4 | x |
| 65 | cube_4 | y |
| 66 | cube_4 | z |
| 67 | cube_4 | qw |
| 68 | cube_4 | qx |
| 69 | cube_4 | qy |
| 70 | cube_4 | qz |
| 71 | cube_4 | vx |
| 72 | cube_4 | vy |
| 73 | cube_4 | vz |
| 74 | cube_4 | wx |
| 75 | cube_4 | wy |
| 76 | cube_4 | wz |
| 77 | cube_4 | bb_x |
| 78 | cube_4 | bb_y |
| 79 | cube_4 | bb_z |
| 80 | kitchen_cooking_area | x |
| 81 | kitchen_cooking_area | y |
| 82 | kitchen_cooking_area | z |
| 83 | kitchen_cooking_area | qw |
| 84 | kitchen_cooking_area | qx |
| 85 | kitchen_cooking_area | qy |
| 86 | kitchen_cooking_area | qz |
| 87 | kitchen_cooking_area_upper | x |
| 88 | kitchen_cooking_area_upper | y |
| 89 | kitchen_cooking_area_upper | z |
| 90 | kitchen_cooking_area_upper | qw |
| 91 | kitchen_cooking_area_upper | qx |
| 92 | kitchen_cooking_area_upper | qy |
| 93 | kitchen_cooking_area_upper | qz |
| 94 | kitchen_island | x |
| 95 | kitchen_island | y |
| 96 | kitchen_island | z |
| 97 | kitchen_island | qw |
| 98 | kitchen_island | qx |
| 99 | kitchen_island | qy |
| 100 | kitchen_island | qz |
| 101 | kitchen_left_corner | x |
| 102 | kitchen_left_corner | y |
| 103 | kitchen_left_corner | z |
| 104 | kitchen_left_corner | qw |
| 105 | kitchen_left_corner | qx |
| 106 | kitchen_left_corner | qy |
| 107 | kitchen_left_corner | qz |
| 108 | kitchen_left_side | x |
| 109 | kitchen_left_side | y |
| 110 | kitchen_left_side | z |
| 111 | kitchen_left_side | qw |
| 112 | kitchen_left_side | qx |
| 113 | kitchen_left_side | qy |
| 114 | kitchen_left_side | qz |
| 115 | robot | pos_base_x |
| 116 | robot | pos_base_y |
| 117 | robot | pos_base_rot |
| 118 | robot | pos_arm_joint1 |
| 119 | robot | pos_arm_joint2 |
| 120 | robot | pos_arm_joint3 |
| 121 | robot | pos_arm_joint4 |
| 122 | robot | pos_arm_joint5 |
| 123 | robot | pos_arm_joint6 |
| 124 | robot | pos_arm_joint7 |
| 125 | robot | pos_gripper |
| 126 | robot | vel_base_x |
| 127 | robot | vel_base_y |
| 128 | robot | vel_base_rot |
| 129 | robot | vel_arm_joint1 |
| 130 | robot | vel_arm_joint2 |
| 131 | robot | vel_arm_joint3 |
| 132 | robot | vel_arm_joint4 |
| 133 | robot | vel_arm_joint5 |
| 134 | robot | vel_arm_joint6 |
| 135 | robot | vel_arm_joint7 |
| 136 | robot | vel_gripper |
| 137 | wiper_0 | x |
| 138 | wiper_0 | y |
| 139 | wiper_0 | z |
| 140 | wiper_0 | qw |
| 141 | wiper_0 | qx |
| 142 | wiper_0 | qy |
| 143 | wiper_0 | qz |
| 144 | wiper_0 | vx |
| 145 | wiper_0 | vy |
| 146 | wiper_0 | vz |
| 147 | wiper_0 | wx |
| 148 | wiper_0 | wy |
| 149 | wiper_0 | wz |
| 150 | wiper_0 | bb_x |
| 151 | wiper_0 | bb_y |
| 152 | wiper_0 | bb_z |
