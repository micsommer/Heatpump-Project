# Heatpump-Project
Datapipeline for my heatpump
Ziel des Projekts ist es, die Daten, die die Wärmepumpe zu Verfügung stellt automatisch auszuwerten und zu speichern.

Aufgebaut auf einem Skript, dass die API der Wärmepumpe ansteuert und die Rohdaten in eine SQLite Datenbank schreibt.

Meilensteine:

1. Daten zugänglich machen 
2. Erste Daten aufreinigen und Ausfälle korrigieren
3. Erste Daten auswerten
4. Automatisierung aufsetzen
5. Fertige Auswertung graphisch darstellen

Dokumentation:

Vorgehen:
2.1 Erster Blick auf die Daten. 
2.2 Es gibt immer wieder WLAN-Ausfälle. Rausfinden, wie die Ausfälle bemerkbar machen: Fehlende Daten oder None Zeilen

Herausforderungen und Lösungen:
2.2 Beim Auslesen der Rohdaten trat eine korrupte SQLite-Datei auf (malformed disk image).
