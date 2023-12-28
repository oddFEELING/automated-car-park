# 🚘 Automated Parking system

## Table of Contents

- [🚘 Automated Parking system](#-automated-parking-system)
  - [Table of Contents](#table-of-contents)
  - [About ](#about-)
  - [Getting Started ](#getting-started-)
    - [other](#other)
      - [Payamaze Source code changes:](#payamaze-source-code-changes)
    - [Installing](#installing)
  - [Usage ](#usage-)

## About <a name = "about"></a>

This notebook implements a system to get the optimum path to the nearest available parking bay in a parking lot for four vehicles. This would in turn help self driving vehicles to navigate the parking lot while getting the optimum parking spot for the driver

## Getting Started <a name = "getting_started"></a>

Chenge the value of the "count" parameter in the "spawn_parked_vehicles()" function in code cell 4 to any number from 1 - 20, then rerun all cells in the notebook to create new instances everytime.

### other

#### Payamaze Source code changes:

The original source code for payamaze was forked and customized for use in this notebook hence, the offical source code version would give errors if used.

- Added the **'mazeName'** attribute to the **'CreateMaze'** method of maze class to give maze custom name when **'saveMaze'** flag is set to True
- Added the **'windowName'** attribute to the **'CreateMaze'** method of maze class and is used by internal method **'drawMaze()'** function which now serves as the TKinter GUI window title when simulator is started.
- Added color obects:
  - parked_vehicle
  - current_vehicle
  - search_path

### Installing

A step by step series of examples that tell you how to get a development env running.

Open a terminal and navigate to a folder of your choice and run the following code

```shell
Git clone https://github.com/oddFEELING/automated-car-park
```

or

download the project zip directly from Github

## Usage <a name = "usage"></a>

...
