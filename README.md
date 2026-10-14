# Nexus – release

Qui ci sono solo i file pronti di **ArduinoFIO**: Nexus (Windows), la libreria per l'IDE di Arduino e il firmware del pannello HMI. Il codice sta in un repository privato.

Scarica l'ultima versione da **[Releases](https://github.com/SRicci24/Nexus-rilasci/releases/latest)**:

- `Nexus-X.Y.Z.zip`: fai clic destro, **Estrai tutto...**, poi avvia `Nexus.exe`. Si installa per l'utente, senza privilegi di amministratore. Contiene anche la libreria e il firmware del pannello.
- `ArduinoFIO-libreria-X.Y.Z.zip`: la libreria, per installarla a mano.
- `pannello-hmi-X.Y.Z.bin`: il firmware del pannello STM32F746G-DISCO, da copiare sull'unità `DIS_F746NG`.

Nexus si aggiorna da solo a ogni avvio: dal PC della cattedra in rete o, se c'è internet, da qui (legge `versione.txt` dell'ultima release e controlla l'impronta SHA-256 dello ZIP).
