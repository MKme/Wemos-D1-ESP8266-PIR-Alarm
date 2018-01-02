
Erics Super Simple motion sensor alarm system using a Wemos D1 mini and Passive infra-red (PIR) sensor to send you notifications via IFTTT
My Youtube Channel  : http://www.youtube.com/mkmeorg
My website   : http://www.mkme.org

If you use this code or personalize it etc- please consider sharing it back with the world Open-Source 
Tested with Arduino IDE 1.6.7
Connect PIR sensor V+ to 5V , V- to GND and Signal as per the sketch below.

Buy the Wemos D1 Here: http://amzn.to/2lFkeA6
Buy the PIR sensor here: http://amzn.to/2lFYh3J
 
V1 Basic Sketch Works to send emails every 10 seconds or around there.
V2 works smoke and motion
V3 Wont boot if d8 high on startup- Changed to Pin 7 and this works. Levelconverter in place and tested- works perfect for 5V in
   Note: MQ2 draws too much for board to support and will need standalone Vref

V4 converting to IFTTT and temporarily removed smoke detection. Disabled wificlient in setup and only activate when ifttt is called- power savings

<p align="center">
  <img src="https://github.com/MKme/WemosAlarm/blob/master/Photos/2017-12-30%2019.02.32.jpg" width="800"/>
</p>

