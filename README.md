# TwinCAT-Linear-Achse-Antrieb

Beckhoff / TwinCAT 3 Linear Achse mit Servo-Antrieb steuern

Der FB wird verwendet um eine Linear-Achse anzusteuern.
Die Antriebe die verwendet werden, besitzen absolut-multi-turn Drehgeber. Eine referenzierfahrt ist somit hinnfällig.
Besonders ist, dass ein abgegebener Fahrauftrag nicht zu ende gefahren werden muss. Es ist möglich einen aktuelleren
Fahrauftrag abzugeben und damit einen aktuellen Fahrauftrag abzulösen.

Benötigte Bibliotheken:
	-> Tc2_MC2
	
Benötigte Lizensen:
	-> TF5000
