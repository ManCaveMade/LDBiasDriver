## LDBiasDriver
Copyright Mitchell A. Cox (mitch@enox.co.za)

If you use this design, please acknowledge me in any resulting publications.

### What is it?

*A low noise laser diode bias driver which uses the ThorLabs MLD203P1 constant power and also the MLD203CLN constanct current (better for fast modulation systems which use a Bias-Tee) bias driver.

https://www.thorlabs.com/thorproduct.cfm?partnumber=MLD203P1
https://www.thorlabs.com/thorproduct.cfm?partnumber=MLD203CLN

*A Arduino based controller for the CC version is WIP. This controller will allow greater than 12 bits of control of the output current as well as digital monitoring of the actual current, etc. I also plan on creating a user friendly MATLAB GUI for it.

#### Features

* Input voltage: 6 - 18 V
* Output current: < 200 mA @ 3.0 V
* Laser current monitor output: 0.1V/mA wrt. GND (can be changed by changing resistors on op-amp)
* Over current protection resistor (R3)
* Sexy red power on LED
* Compact
* SMA for DC bias output (easy connection direct to Bias-Tee)
* ~3 uA noise
 
Designed with Eagle 7.7
