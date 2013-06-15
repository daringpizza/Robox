Robox
=====

##Building, Wiring and Programming.

###Slideshow: The Making of Robox
Nicky Ringland's Slideshow showing how to make the robot: 
https://plus.google.com/photos/111905613472490788948/albums/5885754330336139153

###Wiring Diagram: Robox.fzz
(Diagram created via <a href="http://www.fritzing.com">Fritzing</a>)

###Program: Robox.ino
(included in main repository above)


##Build, Wire, and Program

With a cardboard chassis, students truly build the robot completely using off the shelf components (a funduino, jumper wires, continuous-rotation servos, a 9V battery, and a 9V holder).



##Credits

Contained in this file is the fruits of collaboration between awesome coders and educators who envision use of this platform in their classes.

Credits to Nicky Ringland of Sydney Universisty for naming the robot, coding the Direction-Decision-Making code (Based on measurements from the Ultrasonic-Distance-Sensor), and for creating the slideshow which covers construction (link here).
(Thanks also for providing the name for the project). 

Credits to Chris Newton for his enthusiasm, support, and offering use of his classroom's computers for the afterschool activity.  
We worked out a way to control the robot movement more intuitively 
(
Forward(100);//drive the motors 100%-power forward 
delay(1000);//wait 1 second
//etc.
)

Credits to Conor Hayes for his contributions to the Ultrasonic-Distance-Sensor based Direction-Decision-Making code posted here.
We worked together on a software-patch for fixing the mysterious behavior which only showed itself when powered from the 9V battery and not when plugged into the computer.  
This was resolved via briefly suspending servo-signaling-and-movement during the distance-measurements.

Credits to students who came to Viz Valley Middle School's Afterschool-Robotics-Activity for their innovations and improvements to the Robo

Credits to William and Jane Fujimoto for their work and enthusiasm through the prototyping stages.

Credits to <a href="http://www.techlabeducation.com">TechLab Education</a> for their investment in continued development of the open-source platform.
