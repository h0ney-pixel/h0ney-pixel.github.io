---
title: "Heimnetzwerk - Kurzanleitung"
---

Willkommen! Diese Seite erklärt die wichtigsten Geräte im Heimnetzwerk und was zu tun ist, wenn etwas nicht funktioniert. Die Links hier öffnen sich nur, wenn du mit dem WLAN "Home" verbunden bist.

---

## 🎯 Was du wissen musst

Unser Netzwerk besteht aus drei Haupt-Komponenten:

1. **Modem** - bringt das Internet ins Haus
2. **Router** - verteilt das Internet an alle Geräte und verwaltet das WLAN
3. **Home Assistant** - steuert die Smart-Home-Geräte (Lichter, Heizung, Kameras)

---

## 📍 Geräte & Zugangsdaten

Die Zugangsdaten (Benutzername und Passwort) sind alle im Passwortmanager gespeichert.

| Gerät | Was es macht | Web-Adresse | Eintrag im Passwortmanager |
|-------|--------------|-------------|----------------------------|
| 📡 **Internet Modem** (Draytek) | Bringt Internet ins Haus | http://192.168.1.111 | Internet Modem Draytek |
| 🖥️ **Router** (Unifi Dream Machine Pro) | Verteilt Internet und WLAN | https://192.168.1.1 | Ubiquiti Unifi |
| 🏠 **Home Assistant** | Steuert das ganze Smart Home | http://192.168.1.247:8123 | Home Assistant |

> 💡 **Hinweis fürs Handy:** Die Tabelle ist breit - du kannst sie seitwärts scrollen, falls nötig.

---

## 🔧 Was tun, wenn das Internet nicht geht?

### Schritt 1: Lichter checken
Geh zum **Netzwerkregal** und schau, ob die LED-Lichter an den Geräten normal leuchten.

- **Modem**: Die "Internet"-LED sollte **grün** (oder blinkend grün) sein.
- **Router**: Die Haupt-LED sollte **grün** sein.

Wenn etwas **rot/orange** blinkt oder aus ist → weiter mit Schritt 2.

---

### Schritt 2: Modem neu starten
1. **Stecker ziehen** (vom Modem, das ist das kleinere graue Gerät).
2. **30 Sekunden warten**.
3. Stecker wieder einstecken.
4. Warten, bis alle Lichter wieder normal leuchten (ca. 2-3 Minuten).

Nach dem Neustart prüfen: Geht das Internet wieder?

---

> **Hinweis:** Ein Router-Neustart bringt bei unserem Setup meist nichts, weil das Modem im Bridge-Modus läuft. Falls das Modem ordnungsgemäß funktioniert, sollte der Router automatisch online gehen.

---

### Schritt 3: Im Zweifel bei der Telekom prüfen
Manchmal liegt das Problem beim Internet-Anbieter. Du kannst auf der [Telekom Störungsseite](https://www.telekom.de/störungen) prüfen, ob es bekannte Probleme gibt.

Wenn du dir unsicher bist oder nichts hilft: **Ruf mich an**. Ich helfe gerne!

---

## 📶 WLAN-Probleme

### WLAN ist weg, aber Kabel geht
- Prüfe, ob der **Router** grünes Licht hat.
- Falls ja, aber WLAN immer noch nicht sichtbar: Router neu starten (Stecker ziehen, 10 Sekunden warten, wieder einstecken).
- Danach warten, bis das WLAN wieder erscheint (ca. 2 Minuten).

### WLAN-Passwort vergessen oder ändern
- Das aktuelle WLAN-Passwort steht im **Passwortmanager** unter „WLAN“.
- Ändern kann man es in den [Router-Einstellungen](/udmpro/).

### Gerät findet das WLAN nicht
- Prüfe, ob das WLAN überhaupt aktiv ist (Router-Webseite).
- Stelle sicher, dass du dich mit dem richtigen Netzwerknamen verbindest („Home“).

---

## 🏠 Home Assistant (Smart Home)

Home Assistant ist die Zentrale für alle intelligenten Geräte.

### Was du dort machen kannst:
- Lichter ein-/ausschalten
- Heizung regeln
- Kameras ansehen
- Automationen steuern (z.B. "Gute Nacht"-Modus)

**Wichtig:** Die meisten Geräte funktionieren **auch ohne Internet** – nur Wetterdaten und Kalendereinträge benötigen eine Verbindung.

---

### Was tun, wenn Home Assistant nicht erreichbar ist?
1. Prüfe, ob der **Server/Raspberry Pi** im Netzwerkregal an ist (Lichter am Gerät).
2. Falls aus: Stromstecker prüfen, ggf. neu einstecken.
3. Nach 1–2 Minuten sollte Home Assistant wieder erreichbar sein.
4. Falls immer noch nicht erreichbar: **Ruf mich an**.

---

### Erweiterte Anleitungen
- [Router-Einstellungen (WLAN, Internet)](/udmpro/)
- [Home Assistant – Automationen & Cloud](/homeassistant/)

---

## 🔌 Was funktioniert bei Internetausfall noch?

Bei einem Internetausfall (z.B. Telekom-Störung) läuft unser Smart Home **teilweise weiter**:

✅ **Funktioniert lokal:**
- Alle Lichter und Schalter
- Heizungssteuerung
- Kameras (nur im lokalen Netzwerk)
- Automationen, die keine Internet-Daten brauchen

❌ **Funktioniert NICHT:**
- Wetterdaten auf dem Dashboard
- Kalendereinträge (z.B. Termine)
- Sprachassistenten wie Siri/Google (die brauchen Cloud)

Das bedeutet: Du kannst zu Hause alles wie gewohnt nutzen, solange du im WLAN „Home“ bist – nur externe Informationen fehlen.

---

## 📚 Kleines Glossar

| Begriff | Erklärung |
|---------|-----------|
| **Router** | Verteilt das Internet an alle Geräte (WLAN & LAN) |
| **Modem** | Bringt das Internet von außen ins Haus |
| **Bridge-Modus** | Das Modem macht nur die Internet-Verbindung, der Router übernimmt den Rest |
| **IP-Adresse** | So findet man Geräte im Netzwerk (wie eine Hausnummer) |
| **Dashboard** | Die Übersichtsseite in Home Assistant |
| **LAN** | Kabelnetzwerk – schneller und stabiler als WLAN |
| **WLAN** | Drahtloses Netzwerk (Wi-Fi) |
| **Cloud** | Dienste, die über das Internet laufen (z.B. Wetterdaten) |
| **Lokal** | Funktioniert nur innerhalb des eigenen Netzwerks |

---

**Alles Wichtige ist jetzt auf dieser Seite. Bei Fragen einfach melden!**
