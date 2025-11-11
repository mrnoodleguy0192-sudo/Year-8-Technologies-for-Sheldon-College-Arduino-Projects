So, you've clicked here, lets assume nothing and start from the basics... (Skip to ONCE INSTALLED IF you've started)
First, visit https://www.arduino.cc/en/software/#ide to download the version of whatever you may be running, 

SHELDON USERS (MACOS)

For the Sheldon MacOS users, use Sheldon Self Service Kiosk, and click on Arduino IDE to download the latest version
Then Launch the software and test it

DEFINITIONS OF VARIANTS FOR THE SOFTWARE, MAKE SURE YOU HAVE THE CORRECT VERSION (ZIP FILES EXCLUDED FOR USER SIMPLICITY)

MacOS Apple Silicon, means M series chips offered by Apple themselves, note, DIFFERENT TO INTEL CHIPS (Apple chips may not include JUST the M series chips by the time you read this, but as of 11 Nov of 2025, examples include, the M5 series, M4 PRO and others in the series, M1 series, M2 series, M3 series)

MacOS Intel Silicon, these include chips made by the Intel Foundry, NOT APPLE FOUNDRY! These may include, I series chips (I5, I7, I3, I9, all generations and suffixes)

Linus Applmage, This is for LINUX users ONLY

Windows 10 or Later, this is what non-MACOS users will download, just download the installer package (NOT THE ZIP! OR MSI!) and open after installation


After Download

Make sure you open the installer package you've downloaded, open (double click) and then go through the process as indicated on the installer package


ONCE INSTALLED

1. You should see the Appliance pop-up after installation, here is where the physical comes in handy, if you only have a USB-C port, (the port with a flat o shape) you need to obtain a USB-C male to USB A female
adapter. 

2, You should then connect the USB-A male (the flat rectangle) into the usb-a female and connect the USB-B (the weird connector thats on the arduino) into the arduino. 

3. Connect the Arduino via software, in the left top corner of the IDE application, you can see a white box with the option (Select Board) and you should see an option called (COM4 Arduino [model])

4. This enables the arduino to compile the code in the code box, once you Copy+Paste my code and my setup in real life, you can then press the arrow to compile and automatically run the code.


Physical hardware, what to be advised on... READ THIS! THEY'RE TIPS!

Everything i put in here, is useful, and this will help you a lot.

1. Resistors, they have OHMS, you should always be aware of however many OHMS are on the resistor, usually in the LINQ building, you can find these resistors sorted in ohms, the larger the resistance, the lower the amount of power delivered to the other end
2. LEDs or really any other power consumers within the circuit, have a Cathode and an Anode, the incorrect insertion of this into the breadboard leads to non-functional devices, fix it by just turning it around
3. Switches, THIS is where many people get stuck on, switches are connected, these are meant to go OVER the little trench in the middle of the breadboard, you only need to connect one pair of the two pairs of legs that can be found on the switch, the pushbutton also has four as long as they are connected like   A1-A2 or B1-B2, you can short the circuit and activate whatever you need to activate.
4. RGB LEDs, this LED had RGB pins and a Cathode pin, the cathode is as usual the nagative side, where the current exits.
5. Potentiometers, Terminal 2 is where the positive current enters and Terminal 1 is where the Current exits, Wiper is where the variable power comes out into the analog in row on the arduino, the potentiometer is basically a resistor with a dial, you can change the amount of current going in, therefore adjusts whatever is coded to be controlled by this potentiometer.
6. Temperature nodes, at the LINQ building, we have TMP-36 nodes, they are three feet, the two outermost feet are for power and GND, the middle is the output
7. Ultrasonic distance sensor, you MUST use the Four-feeted Sensors we have if you want compatibility with the code I have provided, they are abunbdant, they won't run out if everyone takes turns.
8. Servos and Motors, These take some knowledge to control (CHATGPT MIGHT NOT ALWAYS BE CORRECT!) and I do not recommend you touch them
9. GND AND 5V, make sure to get these plugged in correctly
10. USE A BREADBOARD! DO NOT MAKE YOUR TINKERCAD ALL OFF OF THE BREADBOARD, THAT'S NOT HOW IT WORKS!
11. The breadboards are connected via vertical rails, they are vertical to the blue and red rails, if you use a double length breadboard, the four side rails aren't auto connected, you should connect them if you plan to use all four. The vertical rails only cover four holes in a vertical line.
