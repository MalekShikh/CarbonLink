Day 1: Watched: [How does Bluetooth Work? (Branch Education)](https://www.youtube.com/watch?v=1I1vxu5qIUM)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Core Concepts: Bluetooth uses a range of 2.4 GHz to a 2.4835 GHz or a 124.9 mm to 120.7 mm wavelength.  
This range is split into 79 different channels, which bluetooth switches through as it transfers information.  
This is to avoid noise and traffic sent out by other devices or routers as they also use the same frequency. It is also used to prevent eavesdropping  
(Routers split the wavelength into only 11-14 channels.)  
When information is sent, it is sent as a packet, its size ranging from 250 to a thousand bits.
The packet is split into three parts, the access code; where it establishes connection and synchronizes with the device, making sure it is the correct  
one, the header; which is information about the bits in the packet, and the payload; which delivers the music or files to the other device.  
Frequency Shift Keying: The shift in frequency which is assigned to a 1 or a 0 to send data.
Device only sends one wave, the carrier wave, which shifts in frequency.
Phase Shift Keying: Another method to transfer data, changes the PHASE* of the wave and the intensity of it is assigned to a value.
&nbsp;  
&nbsp;  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Day 2: Study Radio Antenna theory  
A radio antenna is an interface between wired and wireless, it takes the alternating frequency signal that are sent from radio equipment  
and converts them into wireless electromagnetic waves. In receive mode when electromagnetic waves impact the wires inside the antenna,  
and an electric current is created which is transferred to the reciever.  
Electromagnetic waves are what radio, ultraviolet, light, etc. are made of. They contain both electric and Magnetic properties.  
&nbsp;  
&nbsp;&nbsp;&nbsp;Active Antennas:  
Active antennas are antennas with amplifiers, they send waves using power and amplifies the signals so they can reach your device.  
An example of this is a Wifi router, as it needs to be connected to an outlet in order to function properly, or a bluetooth headphone  
as it requires charging in order to connect and play music. Active antennas can also be recieve only.
&nbsp;  

&nbsp;&nbsp;&nbsp;Passive Antennas:  
Passive antennas are radio antennas that dont have any power of their own, rely on other devices to send waves that induces enough energy  
in their radio antenna that they can reflect waves back.  
An example of this is a NFC card such as a hotel card or a credit card. They require no power however when they come into contact  
with a reader they recieve enough power to recieve and send back waves of information.  Polarization, gain, directivity, resonance, and bandwith are all the same in a passive antenna whether transmitting or recieving.  
&nbsp;  
&nbsp;&nbsp;&nbsp;Day 3: Continue Radio Antenna theory  
Polarization: Orientation of signals recieved and transmitted by an antenna. Most common are vertical and horizontal, however others such as elliptical exist.  

<img width="690" height="313" alt="image" src="https://github.com/user-attachments/assets/b1761600-a409-47ac-b6d0-66f92be0d63c" />  

A antenna with a vertical polarization would need vertical elements to boost signal. EX. 

<img width="402" height="409" alt="image" src="https://github.com/user-attachments/assets/4b263b25-5d0d-4159-a4d1-5071f98e3df8" />  

Mismatched elements with polarization siginificantly decreases signal.
Eliptical or curved polarization is mainly used on antennas that don't need a specific orientation, however elements must still match the rotation.
Used in Satellites, GPS, and some Drone systems. 
Mobile devices use multiple antennas with different polarization, while Bluetooth devices use antennas that radiate in many directions  
so the connection stays stable.  
  
&nbsp;&nbsp;&nbsp;Day 4: Continue Radio Antenna theory  
&nbsp;Feed impedance: Feed impedance is how much a antenna resists to power from the radio. Both the radio and antenna have impedance, usually 50 ohms, and they must  match to work best. For example; if a antenna expects 80 ohms and a radio expects 50 ohms, the mismatch causes reactance and the power to be sent back down the feed or  connection and can damage the radio or reduce range.  
  
&nbsp;Antenna gain and directivity: The gain or directivity of an antenna is how strongly it radiates or recieves signal in different directions,  
as all antennas have a different radiation pattern. An antenna can be designed to recieve or radiate more intensely in different directions.  
  
&nbsp;Antenna resonance: An antenna resonance is when a antena is operated at near frequency so there is only a small amount of reactance,  
making it far easier for the radio to send power. This is also why shorter antennas are better with higher frequencies  
while longer antennas are better at lower frequencies.  

&nbsp;Antenna Bandwidth: Antennas have a bandwidth or range of frequencies over which they can operate well, which is affected by the  
feed impedance, frequency and antenna design.


