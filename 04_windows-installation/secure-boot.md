# Was ist Secure Boot und wofür wird es verwendet?

## 🔐 Einführung

**Secure Boot** ist eine Sicherheitsfunktion moderner Computer mit **UEFI-Firmware**. Sie stellt sicher, dass beim Starten des Systems nur vertrauenswürdige Software geladen wird.

---

## 🔎 Was macht Secure Boot genau?

- Überprüft die digitale Signatur von Betriebssystemen und Treibern beim Start.
- Verhindert, dass Schadsoftware (z. B. Rootkits oder Bootkits) frühzeitig ins System eindringt.
- Blockiert modifizierte oder nicht signierte Bootloader.

📌 **Beispiel**: Wenn ein USB-Stick mit einem unsignierten Linux-Installer verwendet wird, kann der Start blockiert werden.

---

## 🛡️ Vorteile

- Schutz vor Manipulation beim Systemstart
- Erhöhte Sicherheit bei Firmen-PCs und Laptops
- Unterstützt die Integrität von Windows 10/11-Installationen

---

## ❗ Wann kann Secure Boot Probleme machen?

- Beim Installieren alternativer Betriebssysteme wie Linux
- Beim Booten von Live-Systemen oder Backup-Tools
- Wenn nicht signierte Treiber verwendet werden sollen

---

## 🔧 So deaktivierst du Secure Boot (wenn nötig)

1. Rechner neu starten und ins BIOS/UEFI gelangen (z. B. F2 oder Entf)
2. Im Menü „Boot“ oder „Security“ → Secure Boot deaktivieren
3. Ggf. vorher „OS Type“ auf „Other OS“ setzen
4. Änderungen speichern und neu starten

⚠️ **Hinweis**: Bei manchen Geräten muss vorher ein „Supervisor-Passwort“ gesetzt werden.

---

## ✅ Sollte Secure Boot aktiviert bleiben?

- **JA**, wenn du ausschließlich Windows nutzt → bessere Sicherheit
- **NEIN (vorübergehend)**, wenn du Linux, ältere Systeme oder spezielle Tools verwenden willst

Nach der Installation kannst du Secure Boot wieder aktivieren, falls nötig.
