# R3-SoftwareTraining-MuhammadMehdiAli
This project used arduino on thinkercad to create a dual motor system that has 4 different modes, dependent on the dip switch as well as a speed dependent on the potentiometer
As I already have experience with arduino, specifically on thinkercad which was our school's preferred learning platform during quarantine the year before, more of the background knowledged required was already known. I also have experience with wiring such schematics on real breadboards which also aided in this project.
Wiring the schematic was simple for the most part, but there were roadblocks that I encountered along the way. I noticed the battery was not working as a source of power which I later realized was because the ground must be connected to the arduino. I also learned that when wiring the components to the L293D, each must be essentially reflected both on the x and y axis. This posed a slight issue during the output as one of the motors were receiving half of the RPM compared to the other which was due to improper wiring. 
In terms of the coding itself, I didn't face too many issues. The video which taught the bassic coding for a motor was simple and intuitive paired with my prior knowledge make the coding simple.
The code is posted below, but essentially it receives the input from the potentiometer along with the dip switch mode and goes through an if statement to determine the output for the motors, and the value from the potentiometer determines the RPM for the motors.
