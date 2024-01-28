# OpenSR-JVCard
Memory card compatible with famous SR-JV card to the famous Japanese sound modules.<br/>
Designed with DipTrace 3.3.1.1

# May contain bugs
Sorry! Small amount of time :( Feel free to contribute</br>
At this moment there isn't the PCB design. I am very very bad at this.

# FAQ
1. Why there is ~WE directly connected to the connector +VCC?<br/>
This is for future programming option in TL866. ROMpler has this pin tied to VCC and the direction is always from the FLASH to the ROMpler.
My idea is to create TL866 compatible shield and in order to program it you need the WE pin.

2. Why these address lines are randomly connected?<br/>
This is the address bus order in SR-JV cards. Please look into the JV, XV service manuals, these "random" connections are visible here.<br/>
They did this probably because of easier routing the address bus on the boards.

# Author & License
Michal Zurek, Krakow, Poland 2024<br/>
michalzelectro@gmail.com<br/>
If you like it please give a credit!