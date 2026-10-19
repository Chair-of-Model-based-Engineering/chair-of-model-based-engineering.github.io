---
title: "Entwicklung eines Softwaresystems zur automatischen Bereitstellung von virtuellen Maschinen als Docker-Umgebungen"
year: 2025
---

# Entwicklung eines Softwaresystems zur automatischen Bereitstellung von virtuellen Maschinen als Docker-Umgebungen

**Bachelorarbeit** (abgeschlossen 2025)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

**Beschreibung**

Die vorliegende Bachelorarbeit beschäftigt sich mit der Entwicklung eines webbasierten Softwaresystems zur automatischen Bereitstellung von virtuellen Maschinen als Docker-Lernumgebungen. Ausgangspunkt der Arbeit ist die Problemstellung, dass zwar theoretische Grundlagen zu Docker vermittelt werden, jedoch praxisnahe und strukturierte Lernumgebungen für die eigenständige Anwendung dieser Technologie fehlen. Bestehende Lösungen wie Play with Docker bieten lediglich unstrukturierte Sandbox-Umgebungen ohne angeleitete Lernpfade.\\
Das entwickelte System kombiniert moderne Virtualisierungs- und Containerisierungstechnologien zu einer vollautomatisierten Lernplattform. Über eine benutzerfreundliche Weboberfläche können Studierende auf Knopfdruck isolierte virtuelle Maschinen anfordern, die innerhalb einer Minute vollständig konfiguriert und mit vorinstallierten Docker-Umgebungen bereitgestellt werden. Die Architektur basiert auf Proxmox VE als Hypervisor-Plattform, einem Python-FastAPI-Backend und einem Vue.js-Frontend für die Benutzerinteraktion. Webbasierte Terminals ermöglichen den direkten Zugriff auf die bereitgestellten Umgebungen, während ein dokumentbasiertes Übungsframework mit automatischer Aufgabenvalidierung strukturierte Lernszenarien bietet, die vom Betreiber der Software problemlos erstellt werden können.\\
Ein besonderes Augenmerk wurde auf die Sicherheit des Systems gelegt. Durch den Einsatz von KVM-basierten virtuellen Maschinen wird eine starke Isolation zwischen verschiedenen Benutzersitzungen gewährleistet. Penetrationstests deckten anfangs noch Sicherheitslücken auf, die jedoch erfolgreich behoben werden konnten. Das System nutzt Infrastructure-as-Code-Prinzipien mit Ansible für die automatisierte Konfiguration und implementiert eine mehrschichtige Sicherheitsarchitektur mit eingeschränkten Docker-Befehlen und isolierten Netzwerksegmenten.\\
Die Evaluation zeigt, dass die ursprünglich formulierten Ziele weitgehend erreicht wurden. Das System ermöglicht eine vollautomatisierte Bereitstellung von Docker- Lernumgebungen und wurde erfolgreich in einer produktiven Umgebung mit CI/CDPipeline implementiert. Die Architektur erlaubt eine einfache Erweiterung um weitere Technologien und Übungsszenarien. Die Arbeit zeigt, wie sich moderne Automatisierungstechnologien erfolgreich für praktische Lernumgebungen einsetzen lassen und demonstriert dabei Lösungsansätze für die sichere Bereitstellung containerisierter Umgebungen. Damit leistet die Arbeit einen Beitrag zu den Technologien, die die Bildung im IT-Sektor vorantreibt.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
