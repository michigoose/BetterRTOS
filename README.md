# BetterRTOS
A better version of Rockwell's RTOS (Real to String) Instruction

Rockwell's base RTOS instruction converts a REAL (Floating point) data type to a String datatype. Unfortunately, due to the lack of precision inherent in the REAL dataype, the resulting converted string can often contain a random number of decimal places. This instruction allows the programmer to specify that number, so that the result is consistent.

Import this .L5X file as an Add-On Instruction.
