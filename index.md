---
title: "Dokumentation Heimnetzwerk"
---

Hier versuche ich zusammen zu schreiben, was für einen reibungslosen Betrieb der Netzwerk Komponenten nötig ist.  
Die beschriebenen Links müssen idR aus dem Heimnetz aufgerufen werden.

## Netzwerk Router Unifi Dream Machine Pro

Der Unifi Router im Netzwerkregal ist das Herz des Hausnetzwerks. Dort werden alle Einstellungen für das Internet und das Netzwerk vorgenommen.

- [Unifi Router](https://192.168.1.1/network/default/dashboard)
- Passwort Eintrag: Ubiquiti Unifi
- [Erweiterte Doku](/udmpro/)

## Internet Modem

Falls das Internet ausfällt, kann das Modem (Draytek Vigor 165) neugestartet werden, wenn das nicht hilft, liegt der Fehler wahrscheinlich bei der Telekom/Internet Anbieter. Das Modem läuft im Bridge-Modus.

- [Internet Modem](http://192.168.1.111)
- Passwort Eintrag: Internet Modem Draytek
- LTE Modem aus Backup, falls die Hauptleitung (Telekom) ausfällt. (Nicht nötig für normalen Betrieb)

## Haus Steuerung Home Assistant

Hier sind alle Smart-Home Geräte ansprech- und steuerbar.

- [Home Assistant](http://192.168.1.247:8123/)
- Passwort Eintrag für Admin User: Home Assistant
- Die meisten Geräte funktionieren auch ohne Internetverbindung
