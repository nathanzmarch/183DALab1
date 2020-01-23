# 183DA Design of Robotic Systems: Lab1 


## Physical Experimentation

### Actuation Model
In order to get data to build the actuation model we recorded angular velocities of the left and right motors getting the
time taken for one period of the green arrow. Recording video improved the precision of our data because it is not reliant
on reaction time to get good measurements.

![Angular Velocity](https://github.com/nathanzmarch/183DALab1/blob/master/images/angularvelocity.gif)


We also took measurements to measure linear velocity. We set up the car at the end of a straight line and pushed the timer and the
forward control signal to the car from the wifi interface at the same time and recorded the time for the car to get to the end.

![Linear Velocity](https://github.com/nathanzmarch/183DALab1/blob/master/images/84349782_484165345611995_117579179314118656_n.jpg)

### Sensing Model
The data the fueled our sensing model came from getting sensor readings from the lidar sensors as shown in the video below. We 
held a card on a ruler at increments of 1 cm from 1 cm to 60 cm to test the full range of the sensor.

![Sensor Readings](https://github.com/nathanzmarch/183DALab1/blob/master/images/sensordata.gif)

For the magnometer, we used the serial monitor to get the magnoter values in x and y. We used the Compass app on Iphone to find 
North. Then, we put the car onto the phone at the with the front of the car and the phone pointing directly north. We got the magnometer
reading and then rotated the phone by 10 degrees each time checking the compass and recording the new magnometer readings.

