---
title: "Heimnetzwerk – Kurzanleitung"
---

Willkommen! Diese Seite erklärt die wichtigsten Geräte im Heimnetzwerk und was zu tun ist, wenn etwas nicht funktioniert. Die Links hier öffnen sich nur, wenn du mit dem WLAN „Home“ verbunden bist.

---

## 🎯 Was du wissen musst

Unser Netzwerk besteht aus drei Haupt-Komponenten:

1. **Modem** – bringt das Internet ins Haus
2. **Router** – verteilt das Internet an alle Geräte und verwaltet das WLAN
3. **Home Assistant** – steuert die Smart-Home-Geräte (Lichter, Heizung, Kameras)

---

## 📍 Geräte & Zugangsdaten

| Gerät | Was es macht | Web-Adresse | Benutzer | Passwort |
|-------|--------------|-------------|----------|----------|
| **Internet Modem** (Draytek) | Bringt Internet ins Haus | http://192.168.1.111 | admin | Internet Modem Draytek |
| **Router** (Unifi Dream Machine Pro) | Verteilt Internet und WLAN | https://192.168.1.1 | admin | Ubiquiti Unifi |
| **Home Assistant** | Steuert das ganze Smart Home | http://192.168.1.247:8123 | admin | Home Assistant |

> 🔐 **Tipp:** Alle Passwörter sind auch im Passwortmanager gespeichert.

---

## 🔧 Was tun, wenn das Internet nicht geht?

### Schritt 1: Lichter checken
Geh zum **Netzwerkregal** und schau, ob die LED-Lichter an den Geräten normal leuchten.

- **Modem**: Die „Internet“-LED sollte **grün** (oder blinkend grün) sein.
- **Router**: Die Haupt-LED sollte **grün** sein.

Wenn etwas **rot/orange** blinkt oder aus ist → weiter mit Schritt 2.

---

### Schritt 2: Modem neu starten
1. **Stecker ziehen** (vom Modem, das ist das kleinere graue Gerät).
2. **30 Sekunden warten**.
3. Stecker wieder einstecken.
4. Warten, bis alle Lichter wieder normal leuchten (ca. 2–3 Minuten).

Nach dem Neustart prüfen: Geht das Internet wieder?

---

### Schritt 3: Router neu starten
Wenn das Modem okay ist, aber immer noch kein Internet:

1. **Stecker ziehen** (vom Router, das ist das größere graue Gerät mit dem Bildschirm).
2. **10 Sekunden warten**.
3. Stecker wieder einstecken.
4. Warten, bis der Router hochgefahren ist (ca. 1–2 Minuten).

---

### Schritt 4: Im Zweifel bei der Telekom prüfen
Manchmal liegt das Problem beim Internet-Anbieter. Du kannst auf der [Telekom Störungsseite](https://www.telekom.de/störungen) prüfen, ob es bekannte Probleme gibt.

Wenn du dir unsicher bist oder nichts hilft: **Ruf mich an**. Ich helfe gerne!

---

## 🏠 Home Assistant (Smart Home)

Home Assistant ist die Zentrale für alle intelligenten Geräte.

### Was du dort machen kannst:
- Lichter ein-/ausschalten
- Heizung regeln
- Kameras ansehen
- Automationen steuern (z.B. „Gute Nacht“-Modus)

**Wichtig:** Die meisten Geräte funktionieren **auch ohne Internet** – nur Wetterdaten und Kalendereinträge benötigen eine Verbindung.

---

### Erweiterte Anleitungen
- [Router-Einstellungen (WLAN, Internet)](/udmpro/)
- [Home Assistant – Automationen & Cloud](/homeassistant/)

---

## 📚 Kleines Glossar

| Begriff | Erklärung |
|---------|-----------|
| **Router** | Verteilt das Internet an alle Geräte (WLAN & LAN) |
| **Modem** | Bringt das Internet von außen ins Haus |
| **Bridge-Modus** | Das Modem macht nur die Internet-Verbindung, der Router übernimmt den Rest |
| **IP-Adresse** | So findet man Geräte im Netzwerk (wie eine Hausnummer) |
| **Dashboard** | Die Übersichtsseite in Home Assistant |

---

**Alles Wichtige ist jetzt auf dieser Seite. Bei Fragen einfach melden!**
