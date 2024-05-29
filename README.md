Script per Arma3 che permette di riparare un veicolo dall'action menu, lo script ha un cooldown di 150 secondi di default.

COME USARE:
 - Scaricare i 2 file
 - Inserire il file `repair.sqf` nella stessa cartella del file missione
 - Inserire il contenuto del file `vehicleInit.txt` nell'init di ogni veicolo che si vuole poter riparare

OPZIONALE
Il tempo di cooldown é personalizzabile, per modificarlo:
 - Aprire il file `repair.sqf`
 - Modificare il valore della variabile `_timeForRepair = 150;` con un valore a piacere IN SECONDI 

PER SCARICARE 
PREMERE IL TASTO RELEASE A DESTRA

TODO
 - !!! TESTARE LO SCRIPT SU SERVER !!!
 - AGGIUNGERE CONDIZIONE `_this == _target getPilot`
