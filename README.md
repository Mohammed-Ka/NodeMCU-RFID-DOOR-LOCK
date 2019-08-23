# NodeMCU-RFID-Door-Lock
RFID Door lock using esp8266 with solenoid lock

![Demonstration](Demonstration.jpg)

------------------------------------------------
# Parts Used:
-----------
• NodeMCU v3 Lolin ESP8266 IoT
• NodeMcu ESP8266 Base Plate
• MFRC-522 
• 1 Channel Relay 5V Isolated Module
• Solenoid Door Lock DC 12v
• Power Supply 12v
• RGB LED 5MM
• x2 Resistor 1K Ohm 
• Buzzer 5v
• Broadboard 
• Jumper Cables 


# Schematic:
------------

![Schematic](Schematic.jpg)

# Connections:
---------------
RFID (MFRC-522)

• 3.3v = 3.3v (ESP)
• RST = D3 / PIN20 (ESP)
• GND = GND (ESP)
• IRQ = Not Used
• MISO = D6 / PIN40 (ESP)
• MOSI = D7 / PIN44 (ESP)
• SCK = D5 / PIN36 (ESP)
• SDA = D4 / PIN24 (ESP)



BUZZER 5V:

• SIGNAL = D0 PIN8 (ESP)
• GND = GND (ESP)


RGB LED:

• RED = D2 / PIN16 (ESP)
• GREEN = D1 / PIN12 (ESP)
• GND = GND (ESP)


RELAY:

• GND = GND (ESP)
• VCC = 3.3V / PIN46 (ESP)
• IN1 = D8 / PIN50 (ESP)


Solenoid Lock:

• Solenoid Lock GND = GND +12v Power Supply
• Relay (NO) pin = +12V Power Supply
• Relay (COM) pin = +12v Solenoid Lock
