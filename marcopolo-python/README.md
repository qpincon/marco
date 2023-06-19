# Instructions

## Description

You have a 2 dimentional map with a certain height and width. At coordinates x, y the map can be either earth or water.

An island is a contiguous group of earth coordinates. For instance in the following map there is an island at the top left corner and one at the bottom right:

[[EARTH, EARTH, WATER],

[WATER, WATER, EARTH],

[WATER, EARTH, EARTH]]

Two earth coordinates in diagonal are not considered from the same island.

## Algorithm

Initially all earth coordinates are colored in dark grey.

Run `python main.py` to see the map displayed in front of your eyes. You can make the size vary running `python main.py -H=100 -W=80`. The default sides size is 30.

![intial_image](initial.png)

Find a simple algorithm to color all islands with a different color.

Basically you should see something like that in the end

![final_image](final.png)


## Implementation

Modify the code to implement your algorithm.

You'll find a random color generator with the method `_generate_random_color`.

The edge case where the generated color is the same as a previously generated color is not to be taken into account.
