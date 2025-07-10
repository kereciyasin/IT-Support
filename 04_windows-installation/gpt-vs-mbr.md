# 📌 GPT vs. MBR: Was ist der Unterschied?

## 🧷 1. Was ist GPT und MBR?

### 🔹 MBR (Master Boot Record)
- Ein altes Partitionsschema aus dem Jahr 1983.  
- Unterstützt maximal 2 TB große Festplatten.  
- Kann höchstens **4 primäre Partitionen** enthalten.  
- Am Anfang der Festplatte befindet sich ein kleiner Boot-Code und die Partitionstabelle.  
- Funktioniert mit dem BIOS-System.

### 🔹 GPT (GUID Partition Table)
- Moderneres Partitionsschema, das mit UEFI-Systemen funktioniert.  
- Unterstützt bis zu **9,4 ZB** Speicherplatz (praktisch nahezu unbegrenzt).  
- Bis zu **128 Partitionen** möglich.  
- Bietet Redundanz und Fehlerkorrektur durch Backup-Kopf- und -Tabellen.  
- Standard bei modernen Betriebssystemen wie Windows 10 und 11.

---

## ⚖️ 2. GPT vs. MBR: Wichtige Unterschiede

| Eigenschaft              | MBR                          | GPT                                            |
|--------------------------|------------------------------|------------------------------------------------|
| Maximale Festplattengröße| 2 TB                         | 9.4 ZB                                         |
| Anzahl der Partitionen   | 4 (primär)                   | 128+                                           |
| Unterstützte Systeme     | BIOS                         | UEFI                                           |
| Sicherheit               | Schwach                      | Besser dank CRC32-Prüfsumme                   |
| Backup                   | Nein                         | Ja, enthält Backup-Kopf und -Tabelle          |
| Kompatibilität           | Mit älteren Systemen         | Mit modernen Systemen                         |


## 🔧 3. Was ist UEFI vs. Legacy BIOS?

### 📌 Legacy BIOS
- BIOS (Basic Input Output System) ist die klassische Firmware seit den 1980er Jahren.  
- Initialisiert die Hardware beim Starten des PCs.  
- Unterstützt nur MBR (max. 2 TB und 4 Partitionen).  
- Textbasiertes Interface, nur Tastatursteuerung.  

📌 **Vorteil:** Kompatibel mit älteren Systemen  
📌 **Nachteil:** Keine Unterstützung für große Festplatten oder moderne Features

---

### 🖥️ UEFI
- UEFI (Unified Extensible Firmware Interface) ist die moderne Alternative zum BIOS.  
- Unterstützt GPT, große Festplatten und mehr als 128 Partitionen.  
- Grafische Benutzeroberfläche mit Mausunterstützung  
- Schnellere Bootzeit, bessere Sicherheit (z. B. Secure Boot)

📌 **Vorteil:** Schnell, sicher, zukunftssicher  
📌 **Nachteil:** Funktioniert nicht auf sehr alten Rechnern

---

### 📊 Vergleichstabelle

| Eigenschaft         | Legacy BIOS                  | UEFI                                      |
|---------------------|------------------------------|-------------------------------------------|
| Verbreitung         | Seit den 1980er Jahren       | Seit ~2010                                |
| Festplattengröße    | Bis 2 TB                     | Bis 9.4 ZB                                |
| Partitionen         | Max. 4 primäre               | 128+ GPT                                  |
| Bootgeschwindigkeit | Langsam                      | Schnell                                   |
| Benutzeroberfläche  | Textbasiert (nur Tastatur)   | Grafisch (mit Maus)                       |
| Sicherheit          | Keine                        | Secure Boot etc.                          |
| Kompatibilität      | Altgeräte                    | Neue Geräte                               |
