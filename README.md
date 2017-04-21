# campanella


    README
 
    Written by: Michele Lizzit <michele@lizzit.it>, 25 Apr 2016
    Last update: 25 Apr 2016
    Version: 1.0

    Copyright (c) 2016 Michele Lizzit
     	
    This program is free software: you can redistribute it and/or modify
	it under the terms of the GNU Affero General Public License as published
 	by the Free Software Foundation, either version 3 of the License, or
 	(at your option) any later version.
 	
 	This program is distributed in the hope that it will be useful,
 	but WITHOUT ANY WARRANTY; without even the implied warranty of
 	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 	GNU Affero General Public License for more details.
 		
 	You should have received a copy of the GNU Affero General Public License
 	along with this program.  If not, see <http://www.gnu.org/licenses/>.


Sistema per la gestione delle campanelle

Il sistema è in grado di controllare sia campanelle fisiche, se opportunamente collegate, sia riprodurre suono preimpostato tramite degli altoparlanti, è inoltre dotato di un'interfaccia web configurabile.

Per l'installazione è sufficiente eseguire il file install_script.sh da root, lo script è ancora nelle prime fasi di sviluppo ed è poco testato, è consigliabile fare un backup completo del sistema prima di eseguire lo script.
Il software è stato testato su Raspberry PI model B

Potrebbe essere necessario, dopo l'installazione, disabilitare la console seriale usando il comando raspi-config

I pin sono configurabili modificando i relativi sorgenti python
PIN.BOARD

Pin:
GPIO_CAMPANELLA_PIN = 7
GPIO_LED_RED_PIN = 13
GPIO_LED_GREEN_PIN = 16
GPIO_LED_BLUE_PIN = 18
GPIO_BUTTON_PIN = 15
LCD:
RS_PIN = 19
RW_PIN = 21
ENABLE_PIN = 3
DATA_PIN = 23, 26, 22, 24
