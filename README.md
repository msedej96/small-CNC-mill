# small-CNC-mill
A small CNC milling machine that is primarily intended for milling prototype PCBs, small wooden and plastic parts.

I designed and assembled the construction from custom made aluminum plates and Bosch Rexroth aluminum profiles.
The aluminum panels were cut using a water jet material cutting process. At the end, the panels were milled with a milling machine.

Movement of machine is provided by 3 stepper motors (Nema23, 2 Nm, 3 A) that rotate ball screw spindles (pitch of 5 mm) that have minimal backlash. The motors are connected to the spindles via a "elastomer coupling", which reduces vibrations.
Round supported linear rails are used on all axes.

Stepper motor drivers (Leadshine DM542EU) have the option of reducing the idle current, which significantly reduces the heating of the stepper motors. The drivers also have the option of microstep setting up to 1/256, built-in self-adjustment and anti-resonance function, which improves the performance of the motors.

The controller board (CNC USB controller Mk2/4) has a USB connection to the computer. It can control four stepper motors and two additional consumers such as a milling motor and dust extraction system. Software for controlling the machine with 3D visualization of the machining area is included.

The milling motor (Kress FME1050) is capable of up to 29,000 RPM.

![image](https://github.com/msedej96/small-CNC-mill/assets/103876373/cac82443-61b2-4554-84a3-ba77237547c2)
