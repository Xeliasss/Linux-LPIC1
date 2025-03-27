# 📌 LPIC-1 Linux Cheatsheet

Dieses Cheatsheet enthält wichtige Befehle für die LPIC-1 Zertifizierung.

---
## 📂 Dateisystem & Verzeichnisse

| Befehl | Beschreibung |
|--------|-------------|
| `ls -l` | Detaillierte Anzeige des Verzeichnisinhalts |
| `cd /pfad` | Wechsel in ein Verzeichnis |
| `pwd` | Aktuelles Verzeichnis anzeigen |
| `mkdir ordner` | Neuen Ordner erstellen |
| `rmdir ordner` | Leeren Ordner löschen |
| `rm -r ordner` | Ordner inkl. Inhalt löschen |
| `touch datei.txt` | Leere Datei erstellen |
| `cp quelle ziel` | Datei/Ordner kopieren |
| `mv quelle ziel` | Datei/Ordner verschieben |
| `find / -name datei` | Datei suchen |

---
## 👤 Benutzer & Gruppen

| Befehl | Beschreibung |
|--------|-------------|
| `whoami` | Aktuellen Benutzer anzeigen |
| `id` | Benutzer- und Gruppen-IDs anzeigen |
| `adduser name` | Neuen Benutzer hinzufügen |
| `deluser name` | Benutzer entfernen |
| `passwd name` | Passwort eines Benutzers ändern |
| `groupadd name` | Neue Gruppe erstellen |
| `usermod -aG gruppe benutzer` | Benutzer zu einer Gruppe hinzufügen |

---
## 🌐 Netzwerk

| Befehl | Beschreibung |
|--------|-------------|
| `ip a` | IP-Adressen anzeigen |
| `ip r` | Routing-Tabelle anzeigen |
| `ping ziel` | Verbindung testen |
| `netstat -tulnp` | Offene Ports anzeigen |
| `curl -I website.com` | HTTP-Header abrufen |
| `wget url` | Datei von URL herunterladen |

---
## 🚀 System & Prozesse

| Befehl | Beschreibung |
|--------|-------------|
| `uname -a` | Systeminfo anzeigen |
| `top` | Prozesse überwachen |
| `ps aux` | Laufende Prozesse anzeigen |
| `kill PID` | Prozess beenden |
| `df -h` | Festplattenplatz anzeigen |
| `free -m` | RAM-Nutzung anzeigen |
| `uptime` | Laufzeit des Systems anzeigen |

---
## 🔧 Paketmanagement

### 🐧 Debian/Ubuntu (APT)
| Befehl | Beschreibung |
|--------|-------------|
| `apt update` | Paketquellen aktualisieren |
| `apt upgrade` | Installierte Pakete aktualisieren |
| `apt install paket` | Neues Paket installieren |
| `apt remove paket` | Paket entfernen |

### 🎩 Red Hat/CentOS (YUM/DNF)
| Befehl | Beschreibung |
|--------|-------------|
| `dnf install paket` | Neues Paket installieren |
| `dnf remove paket` | Paket entfernen |
| `dnf update` | System aktualisieren |

---
## 🛠️ Sonstiges

| Befehl | Beschreibung |
|--------|-------------|
| `history` | Letzte Befehle anzeigen |
| `alias ll='ls -la'` | Alias erstellen |
| `chmod 755 datei` | Rechte ändern |
| `chown user:gruppe datei` | Besitzer ändern |

---
💡 **Hinweis:** Dieses Cheatsheet wird regelmäßig aktualisiert. Verbesserungen & Pull Requests willkommen! 🚀
