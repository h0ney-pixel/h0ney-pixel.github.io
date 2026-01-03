---
title: "Router (Dream Machine Pro)"
permalink: /udmpro/
---

Der Router steht im Server Schrank und ist der zweite Graue von oben, mit weniger LAN Dosen.

## 🌐 Internet Einstellungen

Die Einstellung für eine Verbindung vom Router zum Internet Provider (Telekom) können [hier](https://192.168.1.1/network/default/settings/internet) gefunden werden.  
Dort muss dann auf "Telekom DSL" geklickt werden, um die Einstellungen zu bearbeiten. In diesen Einstellungen muss ggf. der "Username" und das "Passwort" von Telekom eingetragen werden. Das ist im Passwortmanager unter "Telekom PPPoE" zufinden oder direkt von der Telekom Hotline anzufragen.  

Hierbei handelt es sich um die Zugangsdaten zum Telekomnetz, also das "echte" Internet mit dem sich verbunden wird.

Die bereits getätigten Einstellungen sollten ausreichen, um eine Verbindung zum Internet herzustellen. Falls das nicht der Fall ist, können die Einstellung zurückgesetzt werden:

1. Haken bei "Auto DNS Server"
2. Unter "IPv6 Configuration" -> Disabled aktivieren
3. Haken bei "Smart Queues" entfernen

⚠️ Die Router Website muss nicht unbedingt genauso aussehen, da Updates die Oberfläche verändern können. Die Benennung der Optionen sollte jedoch gleich oder ähnlich bleiben.
![Internet Einstellungen](internet-settings.png)

LTE Modem im Büro kann komplett abgebaut werden, ist nicht nötig für Betrieb.

## 🛜 WLAN Einstellungen

Unter den [WiFi Einstellungen](https://192.168.1.1/network/default/settings/wifi) kann der Name des WLANs und das Passwort dafür geändert werden, indem auf den Namen des WLANs oben geklickt wird. Die aktuellen Namen und Passwörter stehen im Passwortmanager unter "WLAN".

Falls das WLAN nicht mehr funktionieren soll, obwohl eine Verbinung zum Internet besteht, können die Einstellungen und "Advanced" auf "Auto" gesetzt werden, damit sollte ein WLAN Netz aufgebaut werden.

⚠️ Die Router Website muss nicht unbedingt genauso aussehen, da Updates die Oberfläche verändern können. Die Benennung der Optionen sollte jedoch gleich oder ähnlich bleiben.
![WLAN Einstellungen](wifi-settings.png)
