# OOBE\BYPASSNRO: Windows 11 ohne Internetverbindung installieren

## 🧭 Was ist OOBE?

**OOBE (Out-Of-Box Experience)** ist der Setup-Assistent nach der Windows-Installation, bei dem Sprache, Region, Benutzerkonto etc. eingerichtet werden.

---

## 🔧 Was macht BYPASSNRO?

Der Befehl **oobe\bypassnro** überspringt die Anforderung einer Internetverbindung während der OOBE-Phase. Damit kannst du **Windows 11 ohne Microsoft-Konto** und ohne Online-Verbindung einrichten.

---

## 📌 Warum nützlich?

- Lokales Konto statt Online-Zwang
- Nützlich für:
  - Virtuelle Maschinen
  - Firmen-Images
  - Test-Setups
  - Techniker und Administratoren

---

## 🛠️ Anwendung

1. Während der Einrichtung bei „Mit dem Internet verbinden“:
2. Drücke **Shift + F10**, um die Eingabeaufforderung zu öffnen
3. Gib ein: `oobe\bypassnro`
4. Der PC wird neu gestartet
5. Jetzt erscheint die Option „Eingeschränkte Einrichtung“ → lokales Konto möglich

---

## ⚠️ Hinweise

- Diese Methode funktioniert nicht immer in zukünftigen Windows-Versionen
- Nur für fortgeschrittene Nutzer oder Administratoren empfohlen
- Keine Internetverbindung heißt: Kein Online-Update, kein Microsoft-Konto

---

## 📝 Fazit

Mit `oobe\bypassnro` kannst du Windows schnell und flexibel offline installieren – ideal für Testumgebungen und lokale Setups.
