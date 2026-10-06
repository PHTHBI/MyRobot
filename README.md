# MyRobot

Python code for controlling the Dynamixel robot in the databar sessions.

> **Note:** GitLab is still down, so this repository was recreated on short notice and has not been fully tested. If something doesn't work, we will sort it out in the databar.

## Before the databar

- Everything is done in **Python**. Set up Python beforehand, or make sure at least one person in your group has a working Python setup.
- Install Dynamixel Wizard 2.0 (Step 2).
- Watch the introduction video (Step 4).

## Setup

### Step 1: Install Git

Download Git from <https://git-scm.com/install/>.

If you already have Git installed, continue to Step 2.

### Step 2: Install Dynamixel Wizard 2.0

This is one of the two ways we can control the robot. It will be demonstrated in class, but it is a good idea to download and install it before the session:

<https://docs.robotis.com/docs/software/dynamixel_wizard_2_0/introduction/>

### Step 3: Download and install the Dynamixel library

Replace `<insert path to desired directory>` with the folder you want to use, then run the following commands in your command line.

**Windows**

```
cd <insert path to desired directory>
git clone https://github.com/PHTHBI/MyRobot.git
cd MyRobot\DynamixelSDK\python
pip install .
```

**Mac / Linux**

```
cd <insert path to desired directory>
git clone https://github.com/PHTHBI/MyRobot.git
cd MyRobot/DynamixelSDK/python
pip install .
```

### Step 4: Control the robot with the MyRobot Python code

Please watch this video beforehand: <https://youtu.be/wZjfYP7Yaws>

Some of this will also be demonstrated in the databar.

## Problems?

Hopefully everything runs smoothly. If not, we'll figure it out together in the databar.

— Philip