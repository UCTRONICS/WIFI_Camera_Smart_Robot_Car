
# Trouble shooting 
# Let us know if you have any problems and we will try our best to help you.


# Q1: The screen display "connecting ...",but can't control my Robot car and can't the scene from the car’s camera.

A1: 
> 1. Make sure your Robot car has start successfully.When the blue led stop flash and keep on light.

> 2. You should check to ensure you have connect to the 'UCTRONICS' hostpot.


# Q2: I can control the Robot car but can't see the scene from the car's camera.

A2:
> 1. Please try to reconnect your camera, Camera connection exception.Then refresh your APP.

# Q3: I can control my robot car move backword,turn left or right, but can't move forward.What's more,the beep will warning.

A3:
> 1. Check your ultrasonics module to make sure it can work fine,you download the test code from https://github.com/UCTRONICS/Smart-Robot-Car-Arduino/blob/master/UCTRONICS_Smart_Robot_Car/example/ultrasonicTest/ultrasonicTest.ino

> 2. Make sure your battery have enough power, if the battery power is very low, which will influence the ultrasonic woek.

# Q4:  When I click Camera Reset on App,but the robot car's camera can't reset to the center point.

> 1. When assembling the servo, pay attention to the middle position.
> 2. //You can change the center Angle of two steering engines by optimize the below variables
                           /*******************************************************
                                         byte servoXCenterPoint = 88;
                                          byte servoYCenterPoint = 70;
                            **********************************************************/
                            

