# auto_pippety

## pipetty
"Pipetty" is an electronic pipette of Icomes Lab Co., Ltd., [https://www.icomes.co.jp/product/pipetty/](https://www.icomes.co.jp/product/pipetty/).  
The function of liquid handling (aspiration, dispensing) can be controlled through the USB or Bluetooth.

## Hardware of Pipetty
In order to grasp the pipetty and push the tip disposal button by a motor, here are the parts used, as shown in the figure.  
![pipetty](pipetty.png "pipetty")  
The motor with the gear and gear rack is: [https://kitronik.co.uk/products/2595-linear-actuator](https://kitronik.co.uk/products/2595-linear-actuator).

## Hardware of Parallel Gripper
As for the robot arm "Ufactory Lite 6", there is an open-source parallel gripper which can be controlled by position, [OpenParallelGripper](https://github.com/hygradme/OpenParallelGripper).  
Here we used the [XL330_version](https://github.com/hygradme/OpenParallelGripper/blob/main/XL330_version/README.md), and modified the gripper jaws to adapt to different objects, as shown in the figure, ![Modified Gripper](gripper.png "gripper").
