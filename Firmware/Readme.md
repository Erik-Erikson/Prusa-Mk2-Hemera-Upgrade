The firmware changes required for a Hemera upgrade to function normaly have been started. <br>

To create the firmware for your printer you will need to compile it yourself. <br>
I used the Arduino IDE version 1.8.5 <br>

For more detail please read the Prusa github explanation : <br>
https://github.com/prusa3d/Prusa-Firmware/README.md <br>

This firmware is based on Prusa firmware version : 3.2.3 <br>
This is the last firmware Prusa released for the Mk2(s) <br>

This firmware has only been created for the Rambo 1.3 board <br>

<br>

Changes made : <br>

Changes made to  : Configuration_prusa.h <br>
Changed : Nozzle type <br>
Changed : Printer Name <br>
Changed : Manual Home Positions <br>
Changed : MIN and MAX Positions <br>
Changed : Probe Offset from Extruder (Nozzle) <br>
<br>
Changes made to : Marlin_main.cpp <br>
Changed welcome message. <br>
<br>
Changes made to : mesh_bed_calibration.cpp <br>
Changed : Bed_Zero_Ref X and Y to compensate for new extruder to probe offset<br>
