# U-Shaped Gate Detection



The task is real-time detection of yellow and red u-shaped gates using ``C++`` and ``OpenCV`` library. The robot has a mission to cross the yellow gates from above and 
pass through the red gates without any collision to score the relevant point successfully. If there are several gates, the algorithm chooses the closest one for the robot to pass.


# Description


* We open the video camera to capture real-time frames
* Resize the frames to (320,240)
* Process each frame for the probability of gates existence using color and u-shaped gate detection algorithms
* Emit signals when the gate found
* Set up and down signal based on the color of detected gate


# Requirements


* C++ Programming Language (version 11 or higher is suggested)
* OpenCV


# Run


1. Download the repository by clicking on[ this link](https://github.com/kimiaf1998/GateDetection/archive/refs/heads/master.zip " this link") then extract it, or clone it using:
```bash
git clone  https://github.com/kimiaf1998/GateDetection.git
```

2. Open the terminal on the repository directory and compile it using `g++`:
```bash
g++ src/main.cpp -o b_shooter -lsfml-graphics -lsfml-window -lsfml-system
```
Run the ``main.cpp`` file in your IDE
