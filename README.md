# Internet Services
# Teammitglieder: 
- Marco Neuschwander
- Kate Falco
- Janis Müller
### This README.md file is used by this Group to Note down all information related to the Internet Services Project.
---
# Einleitung: 
# Project Explanation 
This Project was started as part of the Module 146 at TBZ. In this Modul we've got the Job to make a Project aboute the Topic "Internet Services".
---
# Inhaltsverzeichnis Theorie: 
-------------------
[1. Übertragunsrate, Verfügbarkeit](Theorie/Übertragunsrate.md "1. Übertragunsrate, Verfügbarkeit")


[2. WAN-Technologie](Theorie/WAN-Technologie.md "2. WAN-Technologie")
   - Beschreibung: Welche Funktionen wird der Service erfuellen
   - Vorgesehener Zeitaufwand für die Realisierung
   - Stolpersteine

[3. Internetservices](Theorie/Internetservices.md  "3. Internetservices" )
   - Hardware (Materialliste, Funktionalitaet)
   - Software (Anforderungen, Firmware, OS-Image, ergaenzende SW-Packages, Ab-
	hängigkeiten, Funktionalitaet)
	
	
[4. Sicherheit](Theorie/Sicherheit.md "4. Sicherheit")
   - Anweisungen verstaendlich und nachvollziehbar
   - Keine fertigen Loesungsschritte aufzeigen
   - Hilfestellung (Tipps, Quellen...)

[5. Wartung / Überwachung](Theorie/Wartung.md "5. Wartung / Überwachung")

[6. Firewall](Theorie/Firewall.md  "6. Firewall")

[7. VPN](Theorie/VPN.md "7. VPN")

[8. Quellen](Theorie/Quellen.md "8. Quellen" )
 

# Inhaltsverzeichnis Vertiefungsthema: 
---
## Composition
- Virtual Box
- Ubuntu Sever LTS 20.04.2 AMD whit User Interface
- Apache Web Server (as mirror)
- 
---
## Issues

- Storage on my virtual disc was firstly scaled by 10 GB afterwards i've added a second vhd with about 64 Gb storage to fight against boot errors. 
quote: Add enough Storage at the first time.
improvements: Add a dedicated HDD to store the repos for the mirror
- due to the Additon of the second vhd i was forced to re isntall the unix enviroment wit more storage.

### Why not to use Azure VM's
As a second try, follwing the Virtual Box VM', we've tried to use Azure Virtual Machines. Firstly they are quite complicated in use. The Price Tag for Education schould be free but about 4 days after we've setted up this vm Janis got an message that about one quarter of the Money was used, the vm consumed money even when its shutted down. 

---

## Work-Flow
df
