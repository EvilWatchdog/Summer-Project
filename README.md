#EVIL WATCHDOG
The project was aimed to build a robot that is capable of patrolling homes, detecting intruders, and pushing notifications to the user’s phones, along with a picture of the intruder. The user can choose to see a live feed from the bot’s perspective, and drive the bot to manually. This could, potentially, replace an array of CCTV cameras, and function as a portable security system, that can be deployed wherever it is required.
Approach: A RaspberryPi Zero W, that is connected to the home’s wifi powers the bot, as it moves through the area, using an ultrasound sensor to detect, and avoid obstacles. A PIR sensor mounted on the bot detects intruders, and activates the camera, that then clicks a picture of the intruder, and uploads it to firebase. This triggers a notification on the android phone, which, upon opening, displays the picture.
Project can be further developed by integrating mobile robotics, mapping of room using mobile robotics, image processing and employing swarm communications between two or more bots.
