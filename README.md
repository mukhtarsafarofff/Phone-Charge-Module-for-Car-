. Actually the MC34063 is the heart of many products that today need a DC-DC converter, that is, a direct voltage converter. The MC34063 is an extremely versatile electronic component that has gained wide acceptance in the electronics world. Its versatility is accompanied by a very convenient price which is an interesting combination. It is a switching regulator that, unlike linear regulators (such as the LM7805), does not dissipate much heat. In my case, my phone needs a charger at 5VDC, that is, the same voltage that a USB port provides us. Because of this, my faulty charger circuit was designed to provide such a voltage at a current of 500mA. With a few changes we can adapt the circuit I will discuss later to provide different voltages.
The chip used is basically the heart of a switched power supply (or switching regulator). That is, it is an oscillator that chops (or divides into portions) the input voltage, according to the required output voltage value.want.

The circuit shows the MC34063 configuration as a step-down regulator and in this configuration the output voltage is given by the following formula :
Vout = 1.25 * (1 + R2 / R1)
In our case R2 = 3.6k and R1 = 1.2K so Vout gives us exactly 5 Volts! To transform our circuit into a USB charger, simply connect a USB terminal to the output by soldering the cables with the correct pinout. 



