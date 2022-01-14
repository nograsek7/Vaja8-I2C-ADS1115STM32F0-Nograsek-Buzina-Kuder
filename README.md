# Vaja8-I2C-ADS1115STM32F0-Nograsek-Buzina-Kuder


V kategoriji Connectivity izberite in omogočite I2C komunikacijo. Kateri pini se aktivirajo? _PB7_ in _PB6_. Koliko različnih I2C komunikacij vaša razvojna plošča omogoča? __2___. 

Sedaj ADS1115 modul povežite z ustreznimi pini na STM32F0. Ne pozabite na upore in kondenzator.  Katere pine ste izbrali? Dopolnite tabelo: 
ADS 1115: 	SCL ;	SDA ;	 ADDR ;	 ALRT ;	       VDD 
STM32F0: 	 PB6	  PB7 	 GND	  (ni povezan) 	 3 V 

V Parameter Settings protokola I2C spremenite Speed Mode na Fast. Koliko znaša sedaj frekvenca? ________8MHz______. 

Vse je delovalo po pričakovanju vendar se ni izšlo brez manših zapletov.
Nismo mogl delat v debagrju in smo mogli vse narediti v sSTM studio ker nismo mogl opklukat Serial wire viewer. 
Poskusili smo tudi brez pull up uporov in vse je delovalo normalno.


Luka Nograšek, Žiga Kuder, Luka Buzina
