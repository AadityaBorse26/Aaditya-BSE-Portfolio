# RFID Attendance System
This is an RFID based card reader that will allow one to check in users using RFID-based scanning. The system also uses an LCD screen to tell if users are checked in or not. A log of users that have checked in or out will be tabulated in a website that can be used to measure attendance. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Aaditya Borse | American High School | Computer Engineering | Incoming Senior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone

My second milestone was installing and setting up my RFID reader. I have already installed the LCD screen, but now I need to test whether the RFID reader is reading my chips and confirming that on the terminal. I soldered the module connection pins onto the RFID, and then wired my circuit to have each connection (MISO, GROUND, etc.) go directly to the RPi Pins. I then installed the MFRC522 library and enabled the SPI interface to communicate with the RC522 module. The read file will allow me to check whether the card was read or not.

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}
# First Milestone

My first Milestone was setting up and installing my LCD screen onto the circuit and breadboard and then testing it. The LCD is a small 6 inch by 4 inch bluelight screen that will indicate when users are checked into the database. By connecting each component's pins into the Raspberry Pi, I had set up my wiring. The 4 wires on the I2C serial interface connect to specific pins on the Raspberry Pi. I then connected power to the Raspberry Pi and then the LCD lit up. To test the LCD display, I had already downloaded the Raspberry Pi OS and the code for the LCD. The code allows me to test the LCD by running a basic clock program. I turned on the Raspberry Pi and ran the test script. The text is correctly displayed onto the LCD display, which shows that the LCD is working as intended. 

[![Aaditya's First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1626280294/video_to_markdown/images/youtube--6jTEs1_C4-A-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/6jTEs1_C4-A "Aaditya's First Milestone"){:target="_blank" rel="noopener"}"

