# P802MA-MKS-base-v1.5-marlin
Marlin 1.1.x firmware for the MKS Base V1.5 on an Anet A8/Tronxy P802MA (AUTO LEVELING)

I modded the a fresh copy of Marlin 1.1.x to enable autoleveling on my P802MA variant of the Anet A8. 

Make sure you verify all settings in the configuration.h file because your Z probe or bed limits may be different than mine. 
Install Arduino 1.8.2

Click tools- Set board type to Arduino Genuino/Mega or Mega 2560 
Set Processor ATMega 2560
Set Com Port

Click "Sketch" - "Include Library" - "Add .ZIP Library" to add the U8Glib library if you are using the MKS TFT32 full graphic display.

Upload and enjoy. 
