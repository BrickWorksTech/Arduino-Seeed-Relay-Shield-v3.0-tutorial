README:
Objective:
This project is designed to be a reminder for me next time I need to wire the seed relay shield together. 
Disclaimer:
Feel free to use the code as you deem fit. I clame no right to the code. If it is taken from another source then they may have rights the code. This is intended for educational use only.
Links to other resources:
http://wiki.seeed.cc/Relay_Shield_v3/
Tutorial:
STEP 1: Load this code into Arduino IDE
motorControl.ino from http://wiki.seeed.cc/Relay_Shield_v3/
int MotorOneControl = 7;    // Digital Arduino Pin used to control the motor

// the setup routine runs once when you press reset:
void setup()  {
  // declare pin 5 to be an output:
  pinMode(MotorControl, OUTPUT);
}

// the loop routine runs over and over again forever:
void loop()  {
  digitalWrite(MotorControl,HIGH);// NO1 and COM1 Connected (the motor is running)
  delay(1000); // wait 1000 milliseconds (1 second)
  digitalWrite(MotorControl,LOW);// NO1 and COM1 Disconnected (the motor is not running)
  delay(1000); // wait 1000 milliseconds (1 second)
}

Step 2: 
Now wire one end of the DC motor to the - end of the battery. 
Step 3:
Wire the other wire to the COM1
Step 4:
Wire NO1 to the positive end of the battery to complete the circuit.
Step 5:
Run the code to see if board/connections are good. Should hear a sound and a LED will light up.

Immages in word doc