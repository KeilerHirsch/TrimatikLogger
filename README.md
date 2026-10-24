# TrimatikLogger

**Eine ältere Heizungsregelung. Deutlich mehr Einblick.**

TrimatikLogger macht Betriebs- und Messdaten einer **Viessmann Trimatik-MC** über einen ESP32-basierten Datenlogger sichtbar. Statt nur den Zustand am Heizgerät abzulesen, lassen sich Temperaturverläufe, Schaltzustände und erfasste Gaszählerimpulse im lokalen Web-Interface betrachten. Messdaten können als CSV oder JSON exportiert werden.

![Beispiel des TrimatikLogger-Web-Interfaces](images/WebIF.png)

## Die Idee

Die Regelbox und die Schaltuhr tauschen Daten aus, die der Logger auswertet. Ein Reed-Kontakt am Gaszähler kann den Verbrauch ergänzen. So werden Vorgänge nachvollziehbar, die sonst in der Heizungssteuerung verborgen bleiben.

**Wichtig:** Die Hardware-Anbindung ist abhängig von der jeweiligen Trimatik-Version. Arbeiten an Heizungssteuerungen und elektrischen Anschlüssen erfordern entsprechende Fachkenntnisse und Sicherheitsmaßnahmen.

## Projekt und Herkunft

Dies ist ein **persönlicher Fork**, keine eigenständige Neuveröffentlichung. Entwicklung, ursprüngliche Beschreibung, Abbildungen und technische Details stammen aus dem Projekt von **[cenders77](https://github.com/cenders77/TrimatikLogger)**. Es wird hier keine eigene getestete Gerätekompatibilität oder aktuelle Release-Freigabe behauptet.

[**Originaldokumentation und Schaltbilder**](docs/ORIGINAL_README.md) · [**Quellprojekt**](https://github.com/cenders77/TrimatikLogger) · [**Quellcode**](TrimatikLogger.ino) · [**Apache-2.0-Lizenz**](LICENSE)

*Kein offizielles Produkt von Viessmann.*
