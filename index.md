# Ball Tracking Robot
My project is to make a ball tracking robot using raspberry pi.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Eddie Zhang | Bellarmine College Preparatory | Computer Science | Incoming Senior

![Pi Logo](https://techround.co.uk/wp-content/uploads/2020/04/Pi-logo.jpeg)
  
# Final Milestone
My final milestone is coding the Pi Camera and the ultrasonic sensor to detect a large red object. The Pi Camera finds red in an image and the ultrasonic sensor senses the distance between the car and the red object. To test, I used the red Raspberry Pi box. In order for the car to be able drive anywhere, I had to use a portable charger to power it. A problem was the weight distribution of the car. Since the portable charger was very heavy, it would cause the car to tip backwards. I solved this by taping the portable charger up further to the front of the car and moving the Raspberry Pi higher. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/PCrpEMkrxeg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
{:target="_blank" rel="noopener"}



# Second Milestone
My second milestone is successfully controlling the motors with Python code and setting up the Pi Camera. I took a few photos to test the Pi Camera and its connection. I inputted the GPIO pins that were connected to the motors into the python script and ran a test where the wheels would move forward, backwards, left, and right. This test was important because it showed me that my motor code was working correctly and that the connections from the solder to the h bridge to the raspberry pi were all correct. A challenge I faced during my second milestone was attatching the Pi Camera to the front of the car; since my first protoype had the Raspberry Pi at the back, the Pi Camera could not reach the front of the car. I then detached the battery pack in the front of the car and moved my Raspberry Pi to the front of the car. There were also a lot of issues with the motor wires falling out of the screw terminals.

<iframe width="560" height="315" src="https://www.youtube.com/embed/gCm8rJnvfTI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
{:target="_blank" rel="noopener"}



# First Milestone
My first milestone was setting up the raspberry pi and building the robot. I wrote the microSD card with Raspberry imager and added extra files in order to successfully complete a headless startup when connected. When conneceted to power with the microSD plugged in, I was able to connect to the Raspberry Pi through Putty and then display the Raspberry Pi screen through VNC Viewer. The second step was to build my robot car. I started by learning how to solder from an instructor, then, I soldered the wires onto the motors and attatched it to the base. After attaching all 3 wheels, I connected the motor wires to the H bridge screw terminals and connected the H bridge to the Raspberry Pi gpio pins. This allows code in the Raspberry Pi to move the car. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/cjJwC9fmZCE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
{:target="_blank" rel="noopener"}
