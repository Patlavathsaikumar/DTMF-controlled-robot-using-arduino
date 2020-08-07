# DTMF-controlled-robot-using-arduino
DTMF Mobile ROBOT is a machine that can be controlled with a mobile.
The robot is controlled by a mobile phone that makes a call to the mobile phone attached to the robot. 
In the course of a call, if any button is pressed, a tone corresponding to the button pressed is heard at the other end of the call. 
This tone is called "Dual Tone Multiple-Frequency" (DTMF) tone. 
The robot perceives this DTMF tone with the help of the phone stacked on the robot. 
The received tone is processed by the Arduino microcontroller with the help of DTMF decoder MT8870
IC the decoder decodes the DTMF tone is to its equivalent binary digit and this binary
number is send to the microcontroller, the microcontroller is pre-programmed to take
decision for any give input and output its decision to motor drivers in order to drive
the motors for forward or backward motion or a turn.
