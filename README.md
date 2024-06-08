# Washing_machine.X
 
### Microcontroller-Based Washing
### Machine Simulation Using PicsimLab 

 1 Overview
 
 1.1 Purpose
 
 REVISION DATE: 20-02-2024
 This project focuses on simulating a washing machine using PicsimLab, aiming to
 replicate real-world washing machine functionality in a virtual environment. The project
 begins with a comprehensive understanding of washing machine components, cycles,
 and operations. Parameters defining laundry status, such as fabric type, load size, and
 water level, are identified.
 
1.2 Scope 
This simulation project provides valuable insights into washing machine operations,
 control system design, and simulation techniques. Participants gain practical experience
 in applying algorithms to simulate intelligent appliances, contributing to a better
 understanding of laundry automation.
 2 Assumptions, Dependencies, Constraints
 
 2.1 Assumptions
 All the peripherals are simulated and no real time objects are interfaced .
 
 2.2 Dependencies
 None
 
 2.3 Constraints
 None
 
3 Requirements

 3.1 Functional Requirements
 Power ON (SW5)
 Pause/stop(SW6)
 Navigation(SW4)
 Door status(SW1)
 
 3.1.1 Power ON Screen
 Microcontroller
 Display
 (Washing Status)
 (CLCD)
 Buzzer
 Motor
 
 Description : As soon as board is reset , print “Press key5 to Power ON Washing 
machine” on the CLCD.
 wait till SW5 is pressed, if SW5 is pressed Print “Powering ON  Washing Machine”.
 
 Requirement No
 1 – POWER ON SCREEN
 Description
 Inputs – SW5 
Process – wait till SW5 is pressed, Turn ON the
 machine 
Output – Print “Powering On Washing Machine”

3.1.2 Washing Program Screen
 Description : The Washing Program menu will contain the following washing options.
 → Daily, Heavy , Delicates, Whites, Stain wash , Eco cottons, Woolens , Bed sheets, 
Rinse+Dry , Dry only, Wash only , Aqua store.
 Using the keypad SW4 we can scroll between the options available. A long press of 
SW4 will select the option highlighted with *
 Requirement No 2 – Washing Program Screen
 Description Inputs – SW5 and SW4
 Process -Washing Program  selection and navigation
 Output - The Washing Program menu will contain the 
following displays
 → Daily, Heavy , Dedicates, Whites, Stain wash , Eco 
cottons, Woolens , Bed sheets, Rinse+Dry , Dry only, 
Wash only , Aqua store
 Washing Programs
 *Daily
 Heavy
 Delicates
 using the keypad SW4 we can scroll between the 
options available.
 A long press of SW4 will select the option highlighted 
with *, switch to the Water level screen.

 3.1.3 Water Level  Screen
 Description : This screen should allow the user to select water level. The water level 
menu will contain the following displays
 → Auto, Low, Medium, High, Low
 Using the keypad SW4 we can scroll between the options available. A long press of 
SW4 will select the option highlighted with *
Requirement No 3 – Water level screen
 Description Inputs -  SW4
 Process – Water level  selection and navigation
 Output -  The water level menu will contain the 
following displays
 → Auto, Low, Medium, High, Max
 Water Level:
 *Auto
 Low
 Medium
 using the keypad SW4 we can scroll between the 
options available.
 A long press of SW4 will select the option highlighted 
with *, switch to start and stop screen

 3.1.4 Start Screen
 Description : Once washing program and water level is selected, provide user option to 
start the machine.
 If SW5 is pressed, start the machine, display the function selected and time taken.
 Then switch to function screen
 Requirement No 4 – Start Screen
 Description Inputs – SW5, SW6
 Process – To Start the operation selected
 Output – Display 
Press Switch :
 SW5: START
 SW6: STOP
 Once SW5 is pressed , display the function selected 
and time. switch to function screen
If SW5 is pressed , display the function selected and 
time. switch to function screen
 Prog: Heavy
 Time: 00:50
 If SW6 is pressed , go back to washing program 
screen.

 3.1.5 Function Screen
 Description : Once machine started , display the function on going , it can be wash, 
rinse or spin. Along with display the time left on the CLCD.
 Requirement No 5 – Function Screen
 Description Inputs -   SW1 , SW5 , SW6.
 Process – Display the function and time left
 Output -  
Display the function and the time left 
function : wash , rinse , spin.
 Time : based on washing program and water level, set 
time.
 If SW5 is pressed start the washing machine
 if SW6 is pressed pause the washing machine 
Function - wash
 TIME : 00:50
 SW5 : START   SW6 : PAUSE 
 
The status of SW1 is indicative of the door status. 
When the switch is pressed, it signifies that the door is 
open; conversely, when the switch is not pressed, it 
indicates that the door is closed." 
If SW1 is pressed turn ON  the buzzer and  display,
 DOOR : OPEN
Please close

 3.1.6 Completion Status Screen 
Description : once all programs are completed, display notification “ Program completed
 Remove clothes ” on the CLCD. 
Requirement No
 1 – Completion screen
 Description
 Output – Print 
“ Program completed
 Remove clothes”                                                                                                                                  
Conclusion :
 The washing machine simulation using picsimlab served as an effective
 tool for learning and applying concepts in embedded systems. It offered a
 hands-on experience that complemented theoretical knowledge and
 provided a foundation for further exploration in the field of automation and
 control systems.
