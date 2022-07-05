# Under Ground Cable Fault Detection System 

# **PROJECT TITLE: Under Ground Cable Fault Detection System**
This project “Underground Cable Fault Detection System” falls under the category of Internet of Things (IOT).
Underground cables are used for power application where it is impractical, difficult or dangerous to use the overhead lines.
They are widely used in densely populated urban areas, in factories and even to supply power from the overhead post to the consumer premises.
Underground electric cables can be particularly hazardous because any damage to the cables can cause fatal or severe injury.
This project focuses on how these faults can be detected by displaying the message on the LCD.

# **OBJECTIVE OF PROJECT:**
The underground cabling system is a common practice followed in many urban areas. There are many electrical, telephone and other signal cables are laid underground. Many time faults occur due to construction works and other reasons. At that time, it is difficult to dig out cable due to not knowing the exact location of the cable fault.
So, the objective of this project is to determine the distance of underground cable fault from base station in kilometers using an Arduino board.

# SCOPE OF PROJECT:
**The scope of the project is as follows:**
#### **This project is capable to measure open circuit fault and short circuit fault.**
### **1. Open Circuit Fault:**
Open Circuit can be detected by measuring the capacitance between two wires.
Capacitance of cable changes according to the length.
The length of cable varies based on the location of cable cut (open). As the cable is open parallel wire capacitance gets reduced based on this, we can calculate the fault location.
### **2. Short Circuit Fault:**
Short circuit can be determined by measuring resistance between two cables at one end (base station). The value of resistance tells us the exact location of short circuit.

The proposed system is to find the exact location of the fault. The project uses the standard concept of Ohms law i.e., when a low DC voltage is applied at the feeder end through a Cable lines, then current would vary depending upon the location of fault in the cable.
In case there is a short circuit (Line to Ground), the voltage across series resistors changes accordingly, which is then fed to inbuilt ADC of Arduino board to develop precise digital data for display in kilometers.
The fault occurring at a particular distance and the respective phase is displayed on a LCD interfaced to the Arduino board.

# SOFTWARE / HARDWARE REQUIREMENT SPECIFICATION:
## **SOFTWARE REQUIREMENT SPECIFICATION:**
1. Arduino IDE

## **HARDWARE REQUIREMENT SPECIFICATION:**
1. Arduino UNO
2. Jumpers - Male to Male, Male to Female, Female to Female
3. Resistor
4. Switch
5. LCD 16x2
6. Potentiometer

# BLOCK DIAGRAM: 
![block](https://user-images.githubusercontent.com/42334113/177245853-09a8b8ec-0efa-47b2-85f8-eb87f387ff5f.png)

# IMPLEMENTATION PROTOTYPE IMAGES:
![block - Copy](https://user-images.githubusercontent.com/42334113/177245865-00d194d7-bf62-4c84-97d2-46c450bcc649.png)
![2](https://user-images.githubusercontent.com/42334113/177248637-38e6fd04-a26b-4477-9c52-d7f677c8b1fd.png)
![3](https://user-images.githubusercontent.com/42334113/177248820-842db25f-d2a2-48c3-b89d-22c3d413c226.png)

