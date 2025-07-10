# Grundbegriffe der Virtualisierung

## 1. Virtualisierung (Virtualization)  
Ermöglicht es, mehrere virtuelle Computer auf einem physischen Computer zu betreiben.  
Beispiel: Auf einem PC gleichzeitig Windows 11 und Linux nutzen.

---

## 2. Hypervisor  
Verwaltet die virtuellen Maschinen und deren Ressourcen.

- **Typ 1:** Direkt auf der Hardware installiert (z. B. VMware ESXi, Hyper-V Server)  
- **Typ 2:** Auf einem bestehenden Betriebssystem installiert (z. B. VMware Workstation, VirtualBox)

---

## 3. Host-System  
Der physische Computer, auf dem virtuelle Maschinen laufen.

---

## 4. Gast-System (Guest)  
Das virtuelle Betriebssystem innerhalb einer virtuellen Maschine.  
Beispiel: Ubuntu, das auf einem Windows-PC als VM läuft.

---

## 5. Virtuelle Maschine (VM)  
Ein vollständig eigenständiger virtueller Computer mit Betriebssystem und Software.

---

## 6. ISO-Datei  
Digitale Installationsdatei eines Betriebssystems – wie eine virtuelle CD/DVD.

---

## 7. Snapshot  
Ein „Foto“ der aktuellen VM-Konfiguration.  
Ermöglicht eine einfache Wiederherstellung zu einem früheren Zustand.

---

## 8. Klonen (Clone)  
Erstellen einer Kopie einer bestehenden VM.

- **Full Clone:** Unabhängige Kopie  
- **Linked Clone:** Abhängig vom Original, spart Speicherplatz

---

## 9. Vorlage (Template)  
Eine vorbereitete VM-Konfiguration, um Zeit bei der Erstellung neuer VMs zu sparen.

---

## 10. NAT (Network Address Translation)  
Die VM nutzt die Internetverbindung des Host-Systems.

---

## 11. Bridged Network  
Die VM erhält eine eigene IP-Adresse und agiert wie ein physischer Rechner im Netzwerk.

---

## 12. Host-Only Network  
Kommunikation nur zwischen Host und VM, ohne Internetzugang.  
Ideal für sichere Testumgebungen.

---

## 13. Testumgebung (Lab Environment)  
Ein virtuelles Netzwerk für Lern- oder Testzwecke, meist mit mehreren VMs.

---

## 14. Verschachtelte Virtualisierung (Nested Virtualization)  
Eine VM läuft innerhalb einer anderen VM.  
Wird in fortgeschrittenen Trainings und Laborumgebungen verwendet.

---

## 15. VM Tools / Guest Additions  
Erweitern die Funktionalität der VM:  
Bessere Grafik, Drag & Drop, Zwischenablage, usw.

---

## 16. Virtuelle Festplatte (Virtual Disk)  
Die Datei, in der das virtuelle Betriebssystem und Daten gespeichert werden.  
Beispiele: `.vmdk` (VMware), `.vdi` (VirtualBox), `.vhdx` (Hyper-V)

---

## 17. Thin vs. Thick Provisioning  
- **Thin:** Speicher wird bei Bedarf zugewiesen  
- **Thick:** Speicherplatz wird im Voraus reserviert  
Relevant für Speicherverwaltung in VMs.
