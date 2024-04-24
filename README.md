. Actually the MC34063 is the heart of many products that today need a DC-DC converter, that is, a direct voltage converter. The MC34063 is an extremely versatile electronic component that has gained wide acceptance in the electronics world. Its versatility is accompanied by a very convenient price which is an interesting combination. It is a switching regulator that, unlike linear regulators (such as the LM7805), does not dissipate much heat. In my case, my phone needs a charger at 5VDC, that is, the same voltage that a USB port provides us. Because of this, my faulty charger circuit was designed to provide such a voltage at a current of 500mA. With a few changes we can adapt the circuit I will discuss later to provide different voltages.
The chip used is basically the heart of a switched power supply (or switching regulator). That is, it is an oscillator that chops (or divides into portions) the input voltage, according to the required output voltage value.want.

The circuit shows the MC34063 configuration as a step-down regulator and in this configuration the output voltage is given by the following formula :
Vout = 1.25 * (1 + R2 / R1)
In our case R2 = 3.6k and R1 = 1.2K so Vout gives us exactly 5 Volts! To transform our circuit into a USB charger, simply connect a USB terminal to the output by soldering the cables with the correct pinout. 

Tatsächlich ist der MC34063 das Herzstück vieler Produkte, die heute einen DC-DC-Wandler benötigen, also einen Gleichspannungswandler. Der MC34063 ist eine äußerst vielseitige elektronische Komponente, die in der Elektronikwelt weit verbreitet und akzeptiert ist. Seine Vielseitigkeit ist mit einem sehr günstigen Preis verbunden, was eine interessante Kombination darstellt.  Es handelt sich um einen Schaltregler, der im Gegensatz zu linearen Reglern (wie dem LM7805) nicht viel Wärme abgibt. In meinem Fall benötigt mein Telefon ein Ladegerät mit 5 VDC, also der gleichen Spannung, die ein USB-Port liefert. Deshalb wurde mein fehlerhafter Ladegerätkreis so entworfen, dass er eine solche Spannung bei einem Strom von 500 mA liefert.  Mit einigen Änderungen können wir den Schaltkreis, den ich später besprechen werde, anpassen, um verschiedene Spannungen zu liefern.

Der verwendete Chip ist im Grunde das Herzstück eines Schaltnetzteils (oder Schaltreglers). Das heißt, er ist ein Oszillator, der die Eingangsspannung entsprechend dem benötigten Ausgangsspannungswert zerkleinert (oder in Portionen teilt).

Die Schaltung zeigt die Konfiguration des MC34063 als Abwärtswandler, und in dieser Konfiguration wird die Ausgangsspannung durch die folgende Formel bestimmt:
Vout = 1,25 * (1 + R2 / R1)
In unserem Fall beträgt R2 = 3,6 k und R1 = 1,2 k, sodass Vout uns genau 5 Volt liefert! Um unseren Schaltkreis in ein USB-Ladegerät zu verwandeln, genügt es, einen USB-Anschluss am Ausgang anzuschließen, indem Sie die Kabel mit der korrekten Pinbelegung verlöten.






