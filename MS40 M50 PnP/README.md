# Speeduino Compatible PCB for BMW M50, Siemens MS40 systems
# Made for MS41 case and connector, with bit of work fitting in MS40 case is possible
SJ5 and SJ6 are used to power optional hall sensors with 5v or 12v. Do not use these with corresponding VR conditioner pins connected (i.e. dont connect (meaning cut/desolder) vr2+,vr2- and out2 pins from vr conditioner for Hall cam sensor)!
In rev 2.2 the power will be sent to pin1 in the sensor connector. Pin 2 will be signal and pin 3 is ground.
If sensors require pull-up resistor, the R39 is used for that for crank and R40 is for cam.
In addition to that R59 and R60 need to be added to get the signal to processor when VR-conditioner is not used.
![backside ms40 pnp board](https://user-images.githubusercontent.com/77926915/109421725-cc27f680-79d8-11eb-8ef7-264b095021e6.png)

