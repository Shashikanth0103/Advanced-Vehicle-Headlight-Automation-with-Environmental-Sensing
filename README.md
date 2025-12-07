# Advanced-Vehicle-Headlight-Automation-with-Environmental-Sensing-
What It Does

This project automates a vehicle’s headlight system using real-time environmental and driving data. The headlights switch between high and low beam automatically, activate fog lights when required, adjust beam spread based on speed, flash high beam on ghat roads when the horn is pressed, and trigger visual alerts during emergencies. All of this happens without manual driver input, improving safety and focus.

# Components Used

1. Arduino Uno

2. LDR (Light Dependent Resistor) for ambient light detection

3. Ultrasonic Sensor for detecting approaching vehicles/objects

4. DHT11 Sensor for fog/humidity monitoring

5. LCD Display for system feedback

6. LEDs / Headlight Modules

7. Buzzer for emergency alerts

#  How to Set Up the Components
1. Connect the LDR
   
* One end to A0 on the Arduino

* Other end to 5V through a resistor

* This measures ambient light for auto high/low beam
  
2. Ultrasonic Sensor (HC-SR04)
* Trig → D9

* Echo → D10

* VCC → 5V

* GND → GND

3. Detects oncoming vehicles or obstacles

* DHT11 Sensor

* Signal → D7

* VCC → 5V

* GND → GND

* Enables fog detection and fog light automation

4.  LCD Display (16x2)

* Connect via I2C

* SDA → A4

* SCL → A5

* Shows speed/mode/status in real time

5. LEDs / Headlight Modules

* High beam, low beam, and fog LEDs connected to digital pins

* Use appropriate resistors and relays for real headlight loads

6. Buzzer

* Signal → D6

7. Alerts during emergency mode

* Horn-trigger Input

* Connect horn line or button to a digital input

* Triggers high-beam flash for ghat roads

## 📸 Photos

![Prototype Setup](https://github.com/Shashikanth0103/Advanced-Vehicle-Headlight-Automation-with-Environmental-Sensing/blob/main/Prototype%20Setup.jpg)
![Foglight](https://github.com/Shashikanth0103/Advanced-Vehicle-Headlight-Automation-with-Environmental-Sensing/blob/main/vehicle%20navigating%20through%20foggy%20conditions%20with%20fog%20lights%20activated%20automatically%20by%20System.png)
![Automatic headlight adjustment](https://github.com/Shashikanth0103/Advanced-Vehicle-Headlight-Automation-with-Environmental-Sensing/blob/main/Automatic%20headlight%20adjustment%20from%20high%20beam%20to%20low%20beam%20when%20an%20oncoming%20vehicle%20is%20detected.png)

