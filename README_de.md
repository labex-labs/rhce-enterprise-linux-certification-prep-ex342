# RHCE-in-Enterprise-Linux-Schulung Certification Prep Path

## Sprachen

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/de/learn/rhce-enterprise-linux"><img width="128px" src="https://file.labex.io/path/VJAk5cEITuZT.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Pfad-Starten-whitesmoke?style=for-the-badge)](https://labex.io/de/learn/rhce-enterprise-linux)

Prepare for the Red Hat Certified Engineer in Enterprise Linux exam (EX342) with a structured, hands-on learning path. This roadmap focuses on RHEL diagnostics and troubleshooting across evidence collection, boot and kernel recovery, file system and LVM repair, package management failures, network connectivity, application and SELinux issues, authentication problems, and crash or investigation artifacts, plus performance-based exam tasks and real-world enterprise scenarios. Guided RHCE in Enterprise Linux courses, labs, and practice exam practice will be added over time to help you build skills aligned with EX342 objectives.

**Kurse**: 3 · **Labs**: 56

## Kurse

### 1. [Vorbereitung auf die RHCE-Zertifizierung für Enterprise Linux (EX342)](https://labex.io/de/courses/rhce-enterprise-linux-prep)

Ein Vorbereitungskurs für die RHCE-Zertifizierung unter Enterprise Linux mit 28 geführten Fehlerbehebungs-Experimenten. Die Themen reichen von der Beweissicherung über Boot-Vorgänge, Speicher, Pakete, Netzwerke, Anwendungen und Authentifizierung bis hin zu fortgeschrittenen Analysemethoden.

[Kurs Starten](https://labex.io/de/courses/rhce-enterprise-linux-prep) · Labs: 28

#### Fehlerbehebungsmethoden und Beweisführung

|   Index | Name                                                                              | Schwierigkeit   | Übung                                                                                                                                      |
|---------|-----------------------------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Erfassung von Basisdaten bei einem Vorfall                                     | Anfänger        | [Labor Starten](https://labex.io/de/labs/collect-baseline-evidence-for-an-incident-664213?course=rhce-enterprise-linux-prep)               |
|       2 | 🧩  Dokumentation, Protokolle und Metriken zur Eingrenzung der Grundursache nutzen | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-documentation-logs-and-metrics-to-narrow-root-cause-664240?course=rhce-enterprise-linux-prep) |
|       3 | 🧩  Zentralisierte Protokollierung und Journal-Persistenz konfigurieren            | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-centralized-logging-and-journal-persistence-664216?course=rhce-enterprise-linux-prep)   |
|       4 | 🧩  Erstellen eines Support-Bundles mit Nachweisen aus der Webkonsole              | Anfänger        | [Labor Starten](https://labex.io/de/labs/gather-a-support-bundle-with-web-console-evidence-664223?course=rhce-enterprise-linux-prep)       |

#### Bootvorgang, Dienste, Kernel und Hardware-Symptome

|   Index | Name                                                         | Schwierigkeit   | Übung                                                                                                                              |
|---------|--------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Diagnose und Reparatur eines fehlerhaften Boot-Dienstes   | Anfänger        | [Labor Starten](https://labex.io/de/labs/diagnose-and-repair-a-failed-boot-service-664218?course=rhce-enterprise-linux-prep)       |
|       2 | 🧩  Root-Zugriff wiederherstellen und Boot-Target korrigieren | Anfänger        | [Labor Starten](https://labex.io/de/labs/recover-root-access-and-restore-boot-target-664231?course=rhce-enterprise-linux-prep)     |
|       3 | 🧩  Bootloader und Kernel-Argument-Drift reparieren           | Anfänger        | [Labor Starten](https://labex.io/de/labs/repair-bootloader-and-kernel-argument-drift-664234?course=rhce-enterprise-linux-prep)     |
|       4 | 🧩  Hardware- und Gerätefehlersignale untersuchen             | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-hardware-and-device-failure-signals-664226?course=rhce-enterprise-linux-prep)     |
|       5 | 🧩  Kernel-Module und persistente Parameter verwalten         | Anfänger        | [Labor Starten](https://labex.io/de/labs/manage-kernel-modules-and-persistent-parameters-664228?course=rhce-enterprise-linux-prep) |

#### Speicherwiederherstellung und Persistenz

|   Index | Name                                                        | Schwierigkeit   | Übung                                                                                                                          |
|---------|-------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Wiederherstellung eines beschädigten Test-Dateisystems   | Anfänger        | [Labor Starten](https://labex.io/de/labs/recover-a-corrupted-test-file-system-664229?course=rhce-enterprise-linux-prep)        |
|       2 | 🧩  LVM-Sichtbarkeit und Mount-Status reparieren             | Anfänger        | [Labor Starten](https://labex.io/de/labs/repair-lvm-visibility-and-mount-state-664236?course=rhce-enterprise-linux-prep)       |
|       3 | 🧩  Daten von einem verschlüsselten Volume wiederherstellen  | Anfänger        | [Labor Starten](https://labex.io/de/labs/recover-data-from-an-encrypted-volume-664230?course=rhce-enterprise-linux-prep)       |
|       4 | 🧩  Diagnose von Problemen mit persistenten Mounts und UUIDs | Anfänger        | [Labor Starten](https://labex.io/de/labs/diagnose-persistent-mount-and-uuid-problems-664221?course=rhce-enterprise-linux-prep) |
|       5 | 🧩  iSCSI-Discovery und persistente Anmeldung reparieren     | Anfänger        | [Labor Starten](https://labex.io/de/labs/repair-iscsi-discovery-and-persistent-login-664235?course=rhce-enterprise-linux-prep) |
|       6 | 🧩  Speicherkapazitätsengpässe beheben                       | Anfänger        | [Labor Starten](https://labex.io/de/labs/resolve-storage-capacity-exhaustion-664239?course=rhce-enterprise-linux-prep)         |

#### Paket- und Systemintegrität

|   Index | Name                                                                    | Schwierigkeit   | Übung                                                                                                                               |
|---------|-------------------------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Beheben von Repository- und Paketabhängigkeitsproblemen              | Anfänger        | [Labor Starten](https://labex.io/de/labs/resolve-repository-and-package-dependency-issues-664238?course=rhce-enterprise-linux-prep) |
|       2 | 🧩  Wiederherstellung der RPM-Datenbank und des Transaktionsstatus       | Anfänger        | [Labor Starten](https://labex.io/de/labs/recover-rpm-database-and-transaction-state-664232?course=rhce-enterprise-linux-prep)       |
|       3 | 🧩  Geänderte Paketdateien identifizieren und wiederherstellen           | Anfänger        | [Labor Starten](https://labex.io/de/labs/identify-and-restore-changed-package-files-664224?course=rhce-enterprise-linux-prep)       |
|       4 | 🧩  Fehlgeschlagene Updates diagnostizieren und Rollback-Optionen nutzen | Anfänger        | [Labor Starten](https://labex.io/de/labs/diagnose-failed-updates-and-rollback-options-664219?course=rhce-enterprise-linux-prep)     |

#### Netzwerk- und Anwendungsstörungen

|   Index | Name                                                              | Schwierigkeit   | Übung                                                                                                                                |
|---------|-------------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Reparatur von NetworkManager, DNS und Routing-Drift            | Anfänger        | [Labor Starten](https://labex.io/de/labs/repair-networkmanager-dns-and-routing-drift-664237?course=rhce-enterprise-linux-prep)       |
|       2 | 🧩  Datenverkehr und Firewall-Service-Pfade untersuchen            | Anfänger        | [Labor Starten](https://labex.io/de/labs/inspect-traffic-and-firewall-service-paths-664227?course=rhce-enterprise-linux-prep)        |
|       3 | 🧩  Identifizierung von Anwendungsbibliotheks- und Laufzeitfehlern | Anfänger        | [Labor Starten](https://labex.io/de/labs/identify-application-library-and-runtime-failures-664225?course=rhce-enterprise-linux-prep) |
|       4 | 🧩  Diagnose von SELinux-Anwendungszugriffsverweigerungen          | Anfänger        | [Labor Starten](https://labex.io/de/labs/diagnose-selinux-application-denials-664222?course=rhce-enterprise-linux-prep)              |
|       5 | 🧩  Einen containerisierten Anwendungsdienst reparieren            | Anfänger        | [Labor Starten](https://labex.io/de/labs/repair-a-containerized-application-service-664233?course=rhce-enterprise-linux-prep)        |

#### Authentifizierung und fortgeschrittene Untersuchung

|   Index | Name                                                                          | Schwierigkeit   | Übung                                                                                                                                  |
|---------|-------------------------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  PAM- und Identitätsabfragefehler diagnostizieren                           | Anfänger        | [Labor Starten](https://labex.io/de/labs/diagnose-pam-and-identity-lookup-failures-664220?course=rhce-enterprise-linux-prep)           |
|       2 | 🧩  Fehlerbehebung bei einem Speicher- oder prozessbasierten Anwendungsproblem | Anfänger        | [Labor Starten](https://labex.io/de/labs/debug-a-memory-or-process-level-application-problem-664217?course=rhce-enterprise-linux-prep) |
|       3 | 🧩  Kernel-Crash-Dump-Nachweise sammeln                                        | Anfänger        | [Labor Starten](https://labex.io/de/labs/collect-kernel-crash-dump-evidence-664214?course=rhce-enterprise-linux-prep)                  |
|       4 | 🧩  Kompilieren und Überprüfen eines sicheren SystemTap-Probes                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/compile-and-check-a-safe-systemtap-probe-664215?course=rhce-enterprise-linux-prep)            |

### 2. [RHCE in Enterprise Linux Übungsprüfung 01](https://labex.io/de/courses/rhce-enterprise-linux-practice-exam-01)

Eine praxisorientierte RHCE in Enterprise Linux Übungsprüfung mit 14 unabhängigen RHEL-Fehlerbehebungsszenarien, die Beweissicherung, Boot-Vorgänge, Speicher, Pakete, Netzwerke, Anwendungen, SELinux, Container, Authentifizierung und SystemTap abdecken.

[Kurs Starten](https://labex.io/de/courses/rhce-enterprise-linux-practice-exam-01) · Labs: 14

#### Fehlerbehebungsmethoden und Beweissicherung

|   Index | Name                                                                      | Schwierigkeit   | Übung                                                                                                                                                       |
|---------|---------------------------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Beweise für einen beeinträchtigten Host sammeln                        | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-collect-evidence-for-a-degraded-host-664461?course=rhce-enterprise-linux-practice-exam-01)                |
|       2 | 🎯  Zentralisierte Protokollierung und Journal-Persistenz wiederherstellen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-restore-centralized-logging-and-journal-persistence-664471?course=rhce-enterprise-linux-practice-exam-01) |

#### Start-, Boot-, Hardware- und Kernel-Probleme

|   Index | Name                                                                                | Schwierigkeit   | Übung                                                                                                                                                           |
|---------|-------------------------------------------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Reparatur einer fehlerhaften Boot-Service-Abhängigkeit                           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-repair-a-failed-boot-service-dependency-664466?course=rhce-enterprise-linux-practice-exam-01)                 |
|       2 | 🎯  Wiederherstellung des Zugriffs nach Kernel- oder Boot-Konfigurationsabweichungen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-restore-access-after-kernel-or-boot-configuration-drift-664470?course=rhce-enterprise-linux-practice-exam-01) |

#### Probleme mit Dateisystemen, LVM, Verschlüsselung und iSCSI

|   Index | Name                                                                  | Schwierigkeit   | Übung                                                                                                                                                   |
|---------|-----------------------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Wiederherstellung eines beschädigten Dateisystems und Mount-Status | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-recover-a-corrupted-file-system-and-mount-state-664465?course=rhce-enterprise-linux-practice-exam-01) |
|       2 | 🎯  Reparatur eines unvollständigen LVM-Stacks                         | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-repair-an-incomplete-lvm-stack-664467?course=rhce-enterprise-linux-practice-exam-01)                  |
|       3 | 🎯  Wiederherstellung des verschlüsselten iSCSI-Speicherzugriffs       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-restore-encrypted-iscsi-storage-access-664472?course=rhce-enterprise-linux-practice-exam-01)          |

#### Probleme bei der Paketverwaltung

|   Index | Name                                                     | Schwierigkeit   | Übung                                                                                                                                                    |
|---------|----------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Behebung von Paketdatenbank- und Abhängigkeitsfehlern | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-resolve-package-database-and-dependency-failures-664468?course=rhce-enterprise-linux-practice-exam-01) |

#### Probleme mit der Netzwerkverbindung

|   Index | Name                                                      | Schwierigkeit   | Übung                                                                                                                                                  |
|---------|-----------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Netzwerkerreichbarkeit eines Dienstes wiederherstellen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-restore-network-service-reachability-664473?course=rhce-enterprise-linux-practice-exam-01)           |
|       2 | 🎯  Erfassung von Verkehrsdaten bei einem Routing-Problem  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-capture-traffic-evidence-for-a-routing-problem-664460?course=rhce-enterprise-linux-practice-exam-01) |

#### Probleme mit Anwendungen, SELinux und containerisierten Anwendungen

|   Index | Name                                                           | Schwierigkeit   | Übung                                                                                                                                                     |
|---------|----------------------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Behebung eines Anwendungsabhängigkeits- und Laufzeitfehlers | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-fix-an-application-dependency-and-runtime-failure-664462?course=rhce-enterprise-linux-practice-exam-01) |
|       2 | 🎯  Behebung von SELinux- und Container-Dienstfehlern           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-resolve-selinux-and-containerized-service-failure-664469?course=rhce-enterprise-linux-practice-exam-01) |

#### Probleme bei Authentifizierung und Identität

|   Index | Name                                 | Schwierigkeit   | Übung                                                                                                                           |
|---------|--------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Behebung eines PAM-Anmeldefehlers | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-fix-a-pam-login-failure-664463?course=rhce-enterprise-linux-practice-exam-01) |

#### Abstürze, SystemTap und Analyse von Drittanbieterdaten

|   Index | Name                                                | Schwierigkeit   | Übung                                                                                                                                                 |
|---------|-----------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Crash- und SystemTap-Untersuchungsdaten erfassen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-gather-crash-and-systemtap-investigation-data-664464?course=rhce-enterprise-linux-practice-exam-01) |

### 3. [RHCE in Enterprise Linux Übungsprüfung 02](https://labex.io/de/courses/rhce-enterprise-linux-practice-exam-02)

Eine zweite praxisorientierte RHCE in Enterprise Linux Übungsprüfung mit 14 unabhängigen RHEL-Fehlerbehebungsszenarien, die Beweissicherung, Boot-Vorgänge, Speicher, Pakete, Netzwerke, Anwendungen, SELinux, Container, Authentifizierung und SystemTap abdecken.

[Kurs Starten](https://labex.io/de/courses/rhce-enterprise-linux-practice-exam-02) · Labs: 14

#### Fehlerbehebungsmethoden und Beweissicherung

|   Index | Name                                                                 | Schwierigkeit   | Übung                                                                                                                                                  |
|---------|----------------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Erstellung eines Support-Bundles für einen wiederkehrenden Fehler | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-build-a-support-bundle-for-a-recurring-failure-664474?course=rhce-enterprise-linux-practice-exam-02) |
|       2 | 🎯  Diagnoseerfassung mit Logging konfigurieren                       | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-configure-diagnostic-collection-with-logging-664475?course=rhce-enterprise-linux-practice-exam-02)   |

#### Start-, Boot-, Hardware- und Kernel-Probleme

|   Index | Name                                                  | Schwierigkeit   | Übung                                                                                                                                                   |
|---------|-------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Wiederherstellung eines Systems im Notfallmodus    | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-restore-a-system-stuck-in-emergency-mode-664487?course=rhce-enterprise-linux-practice-exam-02)        |
|       2 | 🎯  Bootloader-Argumente und Gerätesymptome reparieren | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-repair-bootloader-arguments-and-device-symptoms-664481?course=rhce-enterprise-linux-practice-exam-02) |

#### Probleme mit Dateisystemen, LVM, Verschlüsselung und iSCSI

|   Index | Name                                                                            | Schwierigkeit   | Übung                                                                                                                                                          |
|---------|---------------------------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Reparatur eines defekten Logical Volume Mounts                               | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-repair-a-broken-logical-volume-mount-664482?course=rhce-enterprise-linux-practice-exam-02)                   |
|       2 | 🎯  Daten aus einem falsch konfigurierten verschlüsselten Mount wiederherstellen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-recover-data-from-a-misconfigured-encrypted-mount-664480?course=rhce-enterprise-linux-practice-exam-02)      |
|       3 | 🎯  Wiederherstellung von persistentem iSCSI-Speicher nach Kapazitätsengpass     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-restore-persistent-iscsi-storage-after-capacity-outage-664485?course=rhce-enterprise-linux-practice-exam-02) |

#### Probleme bei der Paketverwaltung

|   Index | Name                                             | Schwierigkeit   | Übung                                                                                                                                      |
|---------|--------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Fehlgeschlagene Pakettransaktionen reparieren | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-repair-failed-package-transactions-664483?course=rhce-enterprise-linux-practice-exam-02) |

#### Probleme mit der Netzwerkverbindung

|   Index | Name                                                             | Schwierigkeit   | Übung                                                                                                                                                  |
|---------|------------------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Eine defekte NetworkManager-Route reparieren                  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-fix-a-broken-networkmanager-route-664479?course=rhce-enterprise-linux-practice-exam-02)              |
|       2 | 🎯  Konflikt zwischen Firewall und Dienst-Bindung diagnostizieren | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-diagnose-firewall-and-service-binding-conflict-664478?course=rhce-enterprise-linux-practice-exam-02) |

#### Probleme mit Anwendungen, SELinux und containerisierten Anwendungen

|   Index | Name                                                                  | Schwierigkeit   | Übung                                                                                                                                                     |
|---------|-----------------------------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Fehlerbehebung bei einem abstürzenden Anwendungsprozess            | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-debug-a-crashing-application-process-664477?course=rhce-enterprise-linux-practice-exam-02)              |
|       2 | 🎯  Wiederherstellung eines Podman-Dienstes mit SELinux-Beschränkungen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-restore-a-podman-service-with-selinux-constraints-664486?course=rhce-enterprise-linux-practice-exam-02) |

#### Probleme bei Authentifizierung und Identität

|   Index | Name                                                 | Schwierigkeit   | Übung                                                                                                                                             |
|---------|------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Identitätsprüfung und Anmeldeverhalten reparieren | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-repair-identity-lookup-and-login-behavior-664484?course=rhce-enterprise-linux-practice-exam-02) |

#### Abstürze, SystemTap und Analyse von Drittanbieterdaten

|   Index | Name                                                | Schwierigkeit   | Übung                                                                                                                                            |
|---------|-----------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Erstellen einer sicheren SystemTap-Diagnosesonde | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-create-a-safe-systemtap-diagnostic-probe-664476?course=rhce-enterprise-linux-practice-exam-02) |

## Über LabEx

[LabEx](https://labex.io) ist eine interaktive, praktische Lernplattform für Programmierung und Technologie. Sie kombiniert Labore, KI-Unterstützung und virtuelle Maschinen für eine videofreie, praktische Lernerfahrung. Mit einem strikten 'Learning by Doing'-Ansatz, interaktiven Online-Umgebungen im Browser mit automatisierten Schritt-für-Schritt-Überprüfungen, strukturierter Inhaltsorganisation mit dem Skill-Tree-basierten System, und einer wachsenden Lernressource von 30 Skill Trees und über 6.000 Laboren, [LabEx](https://labex.io) bietet umfassende praktische Bildung. Die Plattform umfasst den Lernassistenten Labby, aufgebaut auf den neuesten KI-Modellen, der eine konversationelle Lernerfahrung bietet.

