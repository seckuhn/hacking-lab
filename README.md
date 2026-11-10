# Cybersecurity Roadmap

Mein persönlicher Lernplan mit dem Ziel, meine Kenntnisse in Hacker-Hardware, Pentesting, Social Engineering, Reverse Engineering und Darknet kontinuierlich auszubauen. 

Zum Nachahmen oder als Inspiration für alle, die ins Thema einsteigen wollen.

Technische Vorkenntnisse bzw. die Bereitschaft in manche Themen selbst einzusteigen wird vorausgesetzt. Ansonsten versuche ich hier alles fail-safe wiederzugeben und zu erklären.

Schaut gerne auf meinem [YouTube-Kanal @seckuhn](www.youtube.com/@seckuhn) vorbei. Solange ich da nicht gesperrt werde, werde ich da Videos zu meinen Themen posten, damit jeder ein Bild davon bekommt, wie diverse Dinge durchgeführt werden. Falls es zur Sperrung kommen sollte, informiere ich hier über andere Kanäle, damit meine Videos euch noch erreichen.

Keine Ahnung was bei Instagram kommt, aber hier: [@seckuhn](https://www.instagram.com/seckuhn).

Hier im Git und in meinem [Blog](https://seckuhn.github.io/hacking-lab/) ist alles was ich tue nachzulesen.

**Lernzeit:** 4+ Stunden täglich  
**Lerntage:** Montag bis Freitag  
**Ziel:** Fortgeschrittene Kenntnisse aufbauen und praktische Fähigkeiten im Bereich IT-Security und Pentesting entwickeln.

---

## Wochenübersicht

| Tag | Schwerpunkt |
|---|---|
| Montag | Hacking Hardware |
| Dienstag | Pentesting |
| Mittwoch | Social Engineering |
| Donnerstag | Reverse Engineering |
| Freitag | Darknet |

---

## Montag – Hacking Hardware

**Ziel:** Elektronik verstehen, eigene Hardware bauen und Hardware-Schnittstellen analysieren.

### Lernthemen

* [ ] Grundlagen der Elektronik: Spannung, Strom und Widerstand
* [ ] Mikrocontroller: Arduino und ESP32
* [ ] GPIO, UART, SPI und I²C
* [ ] Hardware-Gadgets: Flipper Zero, USB Rubber Ducky und Bus Pirate
* [ ] Löten und einfache Schaltungen aufbauen
* [ ] UART-Debugging an eigener Hardware
* [ ] RFID- und NFC-Grundlagen
* [ ] USB-Kommunikation verstehen
* [ ] Eigene Hardware-Projekte entwickeln

### Erste Projekte

* ESP32-Projekt aufbauen
* Einfachen RFID-Leser entwickeln
* UART-Kommunikation untersuchen
* Kleine elektronische Schaltung bauen

---

## Dienstag – Pentesting

**Ziel:** Systeme, Netzwerke und Anwendungen auf Sicherheitslücken untersuchen.

### Lernthemen

* [ ] Pentest-Methodik und Scope
* [ ] Passive und aktive Reconnaissance
* [ ] Nmap: Host Discovery und Port Scanning
* [ ] Service- und Versionserkennung
* [ ] Enumeration von SSH, SMB, FTP und HTTP
* [ ] Web-Security-Grundlagen: OWASP Top 10
* [ ] Burp Suite
* [ ] Wireshark
* [ ] Schwachstellenanalyse mit Nuclei und Greenbone
* [ ] Exploits in legalen Trainingsumgebungen nachvollziehen
* [ ] Privilege Escalation

### Erste Plattformen

* TryHackMe
* Hack The Box Academy

---

## Mittwoch – Social Engineering

**Ziel:** Menschliche Sicherheitsrisiken verstehen und Social-Engineering-Angriffe analysieren.

**Schwerpunkt:** Lesen, Recherche und Fallstudien.

### Lernthemen

* [ ] Grundlagen der Psychologie und Manipulation
* [ ] Pretexting
* [ ] Phishing und Spear-Phishing
* [ ] Baiting
* [ ] OSINT und öffentlich verfügbare Informationen
* [ ] Social-Engineering-Fallstudien
* [ ] Analyse von Phishing-Mails
* [ ] Menschliche Sicherheitsrisiken
* [ ] Awareness-Konzepte
* [ ] Analyse realer Sicherheitsvorfälle

### Rechercheaufgaben

* Bekannte Social-Engineering-Angriffe untersuchen
* Vorgehensweisen dokumentieren
* Verwendete Manipulationstechniken identifizieren
* Warnsignale und Schutzmaßnahmen festhalten

---

## Donnerstag – Reverse Engineering

**Ziel:** Software und Binärdateien analysieren und deren Funktionsweise verstehen.

### Lernthemen

* [ ] Grundlagen von Assembler
* [ ] CPU-Architekturen
* [ ] x86-64 und ARM
* [ ] Speicherverwaltung
* [ ] Binärdateiformate: PE und ELF
* [ ] Statische Analyse mit Ghidra
* [ ] Dynamische Analyse mit GDB und x64dbg
* [ ] Debugging und Breakpoints
* [ ] Call Stacks
* [ ] Strings, Imports und Funktionen analysieren
* [ ] Grundlagen der Malware-Analyse in isolierten Umgebungen

### Erste Projekte

* Kleines C-Programm schreiben und kompilieren
* Eigenes Programm mit Ghidra analysieren
* Funktionen und Programmabläufe nachvollziehen
* Debugging mit GDB ausprobieren

---

## Freitag – Darknet

**Ziel:** Darknet-Strukturen, Communities und Diskussionen rund um IT-Security verstehen.

**Schwerpunkt:** Lesen, Recherche und Beobachtung.

### Lernthemen

* [ ] Grundlagen von Tor
* [ ] Onion-Routing verstehen
* [ ] Darknet, Deep Web und Clearnet unterscheiden
* [ ] Aufbau von Foren und Communities
* [ ] IT-Security-Diskussionen verfolgen
* [ ] Fachbegriffe und typische Abkürzungen verstehen
* [ ] Diskussionen kritisch auf Glaubwürdigkeit prüfen
* [ ] Sicherheitsvorfälle und Datenleaks analysieren
* [ ] Betrugsmaschen und Scams erkennen
* [ ] Rechtliche Grenzen und persönliche Sicherheit

### Rechercheaufgaben

* Tor und Onion-Routing verstehen
* Legale Informationsangebote recherchieren
* Öffentliche Diskussionen lesen
* Neue Fachbegriffe dokumentieren
* Informationen auf Plausibilität überprüfen

**Sicherheitsregeln:** Keine unbekannten Dateien herunterladen oder ausführen. Keine illegalen Marktplätze oder Angebote nutzen. Keine persönlichen Daten preisgeben.

---

## Lernfortschritt

Am Ende jeder Woche dokumentiere ich:

* Was habe ich gelernt?
* Welche Tools habe ich ausprobiert?
* Welche praktischen Übungen habe ich durchgeführt?
* Was habe ich noch nicht verstanden?
* Welche Themen möchte ich vertiefen?

## Dokumentation

Für jedes Thema lege ich zunächst Notizen, Screenshots, Codebeispiele und Projektdateien an. Dabei versuche ich alle Inhalte entsprechend zu sortieren.

```text
hacking-lab/
│
├── README.md
│
├── hardware/
│
├── pentesting/
│
├── social-engineering/
│
├── reverse-engineering/
│
└── darknet/
```

---

**Langfristiges Ziel:** Ein fundiertes Verständnis von IT-Sicherheit entwickeln, praktische Erfahrungen sammeln und mich kontinuierlich in Richtung professionelles Pentesting weiterentwickeln.

Einfach machen Leute, die Uni bringt eh nichts.



