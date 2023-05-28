# Scout-Python-JS-Move
Python prototype application to move the Moorebot Scout robot using a PS3 joystick controller

I used an old PS/3 controller attached via USB on my laptop, then

```
export ROS_MASTER_URI=http://linaro-alip:11311
./jsmove.py
```

Then the robot can be (carefully !) moved, left joystick controls
forward / backward and left / right rotation which the right joystick
controls the sideways strafe movement.

I have to CTRL-\ stop the application, don't know why. I am not (yet) a
Python export so I am for sure missing a ton. My goal was to get something
started, a little moment of success :-)

It may serve others as a piece of inspiration, took me a bit to figure out
the details.
