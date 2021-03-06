<!--
Copyright (c) 2020 Boston Dynamics, Inc.  All rights reserved.

Downloading, reproducing, distributing or otherwise using the SDK Software
is subject to the terms and conditions of the Boston Dynamics Software
Development Kit License (20191101-BDSDK-SL).
-->

# API Example - WASD

This example creates an interface for operating Spot with your keyboard.

## Setup Dependencies
See requirements.txt for the dependencies required for this example. Using pip, these dependencies can be installed using:
```
python -m pip install -r requirements.txt
```

## Running the Example

```
python wasd.py --username USER --password PASSWORD ROBOT_IP
```

When run, this example will create an interface in your terminal listing the controls which are as follows:

| Button             | Functionality            |
|--------------------|--------------------------|
| wasd               | Directional Strafing     |
| qe                 | Turning                  |
| f                  | Stand                    |
| v                  | Sit                      |
| I                  | Take image               |
| T                  | Time-sync                |
| O                  | Video mode               |
| r                  | Self-right               |
| l                  | Return/Acquire Lease     |
| SPACE              | E-stop                   |
| P                  | Motor power & Control    |
| Tab                | Exit                     |

