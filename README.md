# ARPWave-V2.0
Portable, rechargeable ARP wave machine that uses a background frequency and an active frequency. 


Currently using the attached original schematic, but creating a custom PCB for portability and size constraints. The original used a 9V battery which would die about every 6 hours. The goal for the new one is to use one of many extra 18650 Li-Ion cells I have laying around instead. 

Components used:
2X 555 timers (Might go to the 556 for ease)
All NPN = 2N2222 or equiv.
All PNP = 2N2907 or equiv.
All CR/Diodes = 1N914 or equiv. 
All Capacitors = rated at 16V or above
All R's = 1/4 Watt unless stated elsewhere

2X 42TM003-RC Transformers in series (starting at the 8 oHM side for proper voltage delivery) connected to a 3.5mm Jack 
1x 10K Pot for output strength
1x 1M Pot to control the Active pulses per second. 

USB-C Connector for charging/power
Charging/ System Power Path Management IC = BQ24030RHLR (attached datasheet)
Buck Boost IC = TPS61200 (attached datasheet)

Questions/ Hang up's:
Make sure I did the proper schematic and diagram for the BQ24030RHLR 
     - LED Indicator placement for Charging/Battery status
     - Resistance Values in accordance to the 18650 Cell for charge speed etc.
     
Can the nominal 3.7V supply the 9-12V needed through the buck/boost without causing issues?
Do I need any additional protection IC's for the battery i.e. Over discharge, under discharge, etc on top of the BQ24030RHLR?
    - Buck/Boost IC a good one or should I consider something else?
    
To Do: 
Add on/off Switch
Add active mode on/off switch
Correct placement for POTS

Any other considerations?


