---
title: "Dokumentation Heimnetzwerk"
---

Hier versuche ich zusammen zu schreiben, was für einen reibungslosen Betrieb der Netzwerk Komponenten nötig ist.  
Die beschriebenen Links müssen idR aus dem Heimnetz aufgerufen werden.

## Netzwerk Router Unifi Dream Machine Pro

Der Unifi Router im Netzwerkregal ist das Herz des Hausnetzwerks. Dort werden alle Einstellungen für das Internet und das Netzwerk vorgenommen.

- Adresse: <a href="https://192.168.1.1/network/default/dashboard" target="_blank">Unifi Router</a>
- Passwort Eintrag: Ubiquiti Unifi
- <a href="/udmpro/" target="_blank">Erweiterte Doku</a>

## Internet Modem Draytek Vigor 165

Falls das Internet ausfällt, kann das Modem neugestartet werden, wenn das nicht hilft, liegt der Fehler wahrscheinlich bei der Telekom/Internet Anbieter. Das Modem läuft im Bridge-Modus.

- Adresse: <a href="http://192.168.1.111" target="_blank">Internet Modem</a>
- Passwort Eintrag: Internet Modem Draytek
- LTE Modem aus Backup, falls die Hauptleitung (Telekom) ausfällt. 

## Haus Steuerung Home Assistant

Hier sind alle Smart-Home Geräte ansprech- und steuerbar.

- Adresse: <a href="http://192.168.1.247:8123/" target="_blank">Home Assistant</a>
- Passwort Eintrag: Home Assistant
- Die meisten Geräte funktionieren auch ohne Internetverbindung
