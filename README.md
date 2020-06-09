# Multiplexer4067Fast - Arduino Library for the TI 4067 multiplexer
https://github.com/rasprague/Multiplexer4067Fast
--------------------------------------------------
CD4067 Multiplexer library for Arduino et al - a fast and easy driver for TI 4067 chip  
Templated version by rasprague to use digitalWriteFast library https://github.com/NicksonYap/digitalWriteFast

-------------------------------------------------------------------------
based on work by Max MC Costa https://github.com/sumotoy/Multiplexer4067

-------------------------------------------------------------------------------------
## Description
The Texas Instruments CD4067 it's a CMOS multiplexer, you can use to scan 16 analog values  
(example:pots!) and feed any analog input of your processor.

## Wiring
S0,S1,S2,S3 = addressing  
SIG = output to an analog pin  
EN = tied to GND
