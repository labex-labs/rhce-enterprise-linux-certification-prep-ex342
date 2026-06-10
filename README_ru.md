# Обучение RHCE in Enterprise Linux Certification Prep Path

## Языки

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/ru/learn/rhce-enterprise-linux"><img width="128px" src="https://file.labex.io/path/VJAk5cEITuZT.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Начать-Путь-whitesmoke?style=for-the-badge)](https://labex.io/ru/learn/rhce-enterprise-linux)

Prepare for the Red Hat Certified Engineer in Enterprise Linux exam (EX342) with a structured, hands-on learning path. This roadmap focuses on RHEL diagnostics and troubleshooting across evidence collection, boot and kernel recovery, file system and LVM repair, package management failures, network connectivity, application and SELinux issues, authentication problems, and crash or investigation artifacts, plus performance-based exam tasks and real-world enterprise scenarios. Guided RHCE in Enterprise Linux courses, labs, and practice exam practice will be added over time to help you build skills aligned with EX342 objectives.

**Курсы**: 3 · **Лаборатории**: 56

## Курсы

### 1. [Подготовка к сертификации RHCE в Enterprise Linux (EX342)](https://labex.io/ru/courses/rhce-enterprise-linux-prep)

[![Подготовка к сертификации RHCE в Enterprise Linux (EX342)](https://course-cover.labex.io/rhce-enterprise-linux-prep.png?lang=ru)](https://labex.io/ru/courses/rhce-enterprise-linux-prep)

Курс подготовки к RHCE в Enterprise Linux, включающий 28 практических лабораторных работ по устранению неполадок: от сбора данных до решения проблем с загрузкой, хранилищами, пакетами, сетью, приложениями, аутентификацией и глубоким анализом системы.

[Начать Курс](https://labex.io/ru/courses/rhce-enterprise-linux-prep) · Лаборатории: 28

#### Методы устранения неполадок и сбор доказательств

|   Индекс | Название                                                                       | Сложность   | Практика                                                                                                                                        |
|----------|--------------------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Сбор базовых данных для анализа инцидента                                   | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/collect-baseline-evidence-for-an-incident-664213?course=rhce-enterprise-linux-prep)               |
|        2 | 🧩  Использование документации, журналов и метрик для определения первопричины  | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/use-documentation-logs-and-metrics-to-narrow-root-cause-664240?course=rhce-enterprise-linux-prep) |
|        3 | 🧩  Настройка централизованного ведения журналов и постоянного хранения journal | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/configure-centralized-logging-and-journal-persistence-664216?course=rhce-enterprise-linux-prep)   |
|        4 | 🧩  Сбор пакета поддержки с доказательствами из веб-консоли                     | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/gather-a-support-bundle-with-web-console-evidence-664223?course=rhce-enterprise-linux-prep)       |

#### Загрузка, службы, ядро и аппаратные сбои

|   Индекс | Название                                                               | Сложность   | Практика                                                                                                                                |
|----------|------------------------------------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Диагностика и восстановление неисправной службы автозагрузки        | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/diagnose-and-repair-a-failed-boot-service-664218?course=rhce-enterprise-linux-prep)       |
|        2 | 🧩  Восстановление доступа root и целевого состояния загрузки           | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/recover-root-access-and-restore-boot-target-664231?course=rhce-enterprise-linux-prep)     |
|        3 | 🧩  Восстановление загрузчика и устранение отклонений в аргументах ядра | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/repair-bootloader-and-kernel-argument-drift-664234?course=rhce-enterprise-linux-prep)     |
|        4 | 🧩  Проверка оборудования и сигналов об ошибках устройств               | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-hardware-and-device-failure-signals-664226?course=rhce-enterprise-linux-prep)     |
|        5 | 🧩  Управление модулями ядра и постоянными параметрами                  | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/manage-kernel-modules-and-persistent-parameters-664228?course=rhce-enterprise-linux-prep) |

#### Восстановление хранилища и обеспечение постоянства данных

|   Индекс | Название                                                          | Сложность   | Практика                                                                                                                            |
|----------|-------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Восстановление поврежденной тестовой файловой системы          | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/recover-a-corrupted-test-file-system-664229?course=rhce-enterprise-linux-prep)        |
|        2 | 🧩  Восстановление видимости и состояния монтирования LVM          | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/repair-lvm-visibility-and-mount-state-664236?course=rhce-enterprise-linux-prep)       |
|        3 | 🧩  Восстановление данных из зашифрованного тома                   | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/recover-data-from-an-encrypted-volume-664230?course=rhce-enterprise-linux-prep)       |
|        4 | 🧩  Диагностика проблем с постоянным монтированием и UUID          | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/diagnose-persistent-mount-and-uuid-problems-664221?course=rhce-enterprise-linux-prep) |
|        5 | 🧩  Восстановление обнаружения iSCSI и постоянного входа в систему | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/repair-iscsi-discovery-and-persistent-login-664235?course=rhce-enterprise-linux-prep) |
|        6 | 🧩  Устранение нехватки дискового пространства                     | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/resolve-storage-capacity-exhaustion-664239?course=rhce-enterprise-linux-prep)         |

#### Целостность пакетов и системных файлов

|   Индекс | Название                                                      | Сложность   | Практика                                                                                                                                 |
|----------|---------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Устранение проблем с репозиториями и зависимостями пакетов | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/resolve-repository-and-package-dependency-issues-664238?course=rhce-enterprise-linux-prep) |
|        2 | 🧩  Восстановление базы данных RPM и состояния транзакций      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/recover-rpm-database-and-transaction-state-664232?course=rhce-enterprise-linux-prep)       |
|        3 | 🧩  Идентификация и восстановление измененных файлов пакетов   | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/identify-and-restore-changed-package-files-664224?course=rhce-enterprise-linux-prep)       |
|        4 | 🧩  Диагностика неудачных обновлений и варианты отката         | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/diagnose-failed-updates-and-rollback-options-664219?course=rhce-enterprise-linux-prep)     |

#### Сетевые инциденты и проблемы с приложениями

|   Индекс | Название                                                           | Сложность   | Практика                                                                                                                                  |
|----------|--------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Исправление отклонений в NetworkManager, DNS и маршрутизации    | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/repair-networkmanager-dns-and-routing-drift-664237?course=rhce-enterprise-linux-prep)       |
|        2 | 🧩  Проверка сетевого трафика и путей доступа к службам брандмауэра | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/inspect-traffic-and-firewall-service-paths-664227?course=rhce-enterprise-linux-prep)        |
|        3 | 🧩  Выявление сбоев библиотек приложений и среды выполнения         | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/identify-application-library-and-runtime-failures-664225?course=rhce-enterprise-linux-prep) |
|        4 | 🧩  Диагностика отказов приложений в SELinux                        | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/diagnose-selinux-application-denials-664222?course=rhce-enterprise-linux-prep)              |
|        5 | 🧩  Восстановление контейнеризированного сервиса приложения         | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/repair-a-containerized-application-service-664233?course=rhce-enterprise-linux-prep)        |

#### Аутентификация и углубленное расследование

|   Индекс | Название                                               | Сложность   | Практика                                                                                                                                    |
|----------|--------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Диагностика сбоев PAM и поиска идентификаторов      | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/diagnose-pam-and-identity-lookup-failures-664220?course=rhce-enterprise-linux-prep)           |
|        2 | 🧩  Отладка проблем с памятью или процессами приложения | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/debug-a-memory-or-process-level-application-problem-664217?course=rhce-enterprise-linux-prep) |
|        3 | 🧩  Сбор данных о дампе ядра при сбое                   | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/collect-kernel-crash-dump-evidence-664214?course=rhce-enterprise-linux-prep)                  |
|        4 | 🧩  Компиляция и проверка безопасного зонда SystemTap   | Начинающий  | [Начать Лабораторию](https://labex.io/ru/labs/compile-and-check-a-safe-systemtap-probe-664215?course=rhce-enterprise-linux-prep)            |

### 2. [RHCE в Enterprise Linux: Практический экзамен 01](https://labex.io/ru/courses/rhce-enterprise-linux-practice-exam-01)

[![RHCE в Enterprise Linux: Практический экзамен 01](https://course-cover.labex.io/rhce-enterprise-linux-practice-exam-01.png?lang=ru)](https://labex.io/ru/courses/rhce-enterprise-linux-practice-exam-01)

Практический экзамен по RHCE в Enterprise Linux, включающий 14 независимых сценариев по устранению неполадок в RHEL. Задания охватывают сбор диагностических данных, процесс загрузки, управление хранилищами, пакетами, сетью, приложениями, SELinux, контейнерами, аутентификацией и использование SystemTap.

[Начать Курс](https://labex.io/ru/courses/rhce-enterprise-linux-practice-exam-01) · Лаборатории: 14

#### Методы устранения неполадок и сбор доказательств

|   Индекс | Название                                                                         | Сложность   | Практика                                                                                                                                                   |
|----------|----------------------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Сбор доказательств для скомпрометированного хоста                             | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-collect-evidence-for-a-degraded-host-664461?course=rhce-enterprise-linux-practice-exam-01)                |
|        2 | 🎯  Восстановление централизованного логирования и постоянного хранилища journald | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-restore-centralized-logging-and-journal-persistence-664471?course=rhce-enterprise-linux-practice-exam-01) |

#### Проблемы запуска, загрузки, оборудования и ядра

|   Индекс | Название                                                                      | Сложность   | Практика                                                                                                                                                       |
|----------|-------------------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Устранение неисправности зависимости службы при загрузке                   | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-repair-a-failed-boot-service-dependency-664466?course=rhce-enterprise-linux-practice-exam-01)                 |
|        2 | 🎯  Восстановление доступа после отклонений в конфигурации ядра или загрузчика | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-restore-access-after-kernel-or-boot-configuration-drift-664470?course=rhce-enterprise-linux-practice-exam-01) |

#### Проблемы файловой системы, LVM, шифрования и iSCSI

|   Индекс | Название                                                                 | Сложность   | Практика                                                                                                                                               |
|----------|--------------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Восстановление поврежденной файловой системы и состояния монтирования | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-recover-a-corrupted-file-system-and-mount-state-664465?course=rhce-enterprise-linux-practice-exam-01) |
|        2 | 🎯  Восстановление неполного стека LVM                                    | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-repair-an-incomplete-lvm-stack-664467?course=rhce-enterprise-linux-practice-exam-01)                  |
|        3 | 🎯  Восстановление доступа к зашифрованному хранилищу iSCSI               | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-restore-encrypted-iscsi-storage-access-664472?course=rhce-enterprise-linux-practice-exam-01)          |

#### Проблемы управления пакетами

|   Индекс | Название                                               | Сложность   | Практика                                                                                                                                                |
|----------|--------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Устранение сбоев базы данных пакетов и зависимостей | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-resolve-package-database-and-dependency-failures-664468?course=rhce-enterprise-linux-practice-exam-01) |

#### Проблемы сетевого подключения

|   Индекс | Название                                                           | Сложность   | Практика                                                                                                                                              |
|----------|--------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Восстановление доступности сетевой службы                       | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-restore-network-service-reachability-664473?course=rhce-enterprise-linux-practice-exam-01)           |
|        2 | 🎯  Сбор доказательств трафика для решения проблем с маршрутизацией | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-capture-traffic-evidence-for-a-routing-problem-664460?course=rhce-enterprise-linux-practice-exam-01) |

#### Проблемы приложений, SELinux и контейнеризированных приложений

|   Индекс | Название                                                           | Сложность   | Практика                                                                                                                                                 |
|----------|--------------------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Исправление зависимостей приложения и ошибок времени выполнения | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-fix-an-application-dependency-and-runtime-failure-664462?course=rhce-enterprise-linux-practice-exam-01) |
|        2 | 🎯  Устранение сбоев SELinux и контейнеризированных служб           | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-resolve-selinux-and-containerized-service-failure-664469?course=rhce-enterprise-linux-practice-exam-01) |

#### Проблемы аутентификации и идентификации

|   Индекс | Название                       | Сложность   | Практика                                                                                                                       |
|----------|--------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Устранение ошибки входа PAM | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-fix-a-pam-login-failure-664463?course=rhce-enterprise-linux-practice-exam-01) |

#### Анализ сбоев, SystemTap и сторонних данных диагностики

|   Индекс | Название                                                         | Сложность   | Практика                                                                                                                                             |
|----------|------------------------------------------------------------------|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Сбор данных для расследования сбоев и использования SystemTap | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-gather-crash-and-systemtap-investigation-data-664464?course=rhce-enterprise-linux-practice-exam-01) |

### 3. [RHCE в Enterprise Linux: Практический экзамен 02](https://labex.io/ru/courses/rhce-enterprise-linux-practice-exam-02)

[![RHCE в Enterprise Linux: Практический экзамен 02](https://course-cover.labex.io/rhce-enterprise-linux-practice-exam-02.png?lang=ru)](https://labex.io/ru/courses/rhce-enterprise-linux-practice-exam-02)

Второй практический экзамен по RHCE в Enterprise Linux, включающий 14 независимых сценариев по устранению неполадок в RHEL. Задания охватывают сбор диагностических данных, загрузку системы, управление хранилищами, пакетами, сетью, приложениями, SELinux, контейнерами, аутентификацией и SystemTap.

[Начать Курс](https://labex.io/ru/courses/rhce-enterprise-linux-practice-exam-02) · Лаборатории: 14

#### Методы устранения неполадок и сбор доказательств

|   Индекс | Название                                                               | Сложность   | Практика                                                                                                                                              |
|----------|------------------------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Создание пакета поддержки для повторяющегося сбоя                   | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-build-a-support-bundle-for-a-recurring-failure-664474?course=rhce-enterprise-linux-practice-exam-02) |
|        2 | 🎯  Настройка сбора диагностических данных с использованием логирования | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-configure-diagnostic-collection-with-logging-664475?course=rhce-enterprise-linux-practice-exam-02)   |

#### Проблемы запуска, загрузки, оборудования и ядра

|   Индекс | Название                                                    | Сложность   | Практика                                                                                                                                               |
|----------|-------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Восстановление системы, застрявшей в аварийном режиме    | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-restore-a-system-stuck-in-emergency-mode-664487?course=rhce-enterprise-linux-practice-exam-02)        |
|        2 | 🎯  Исправление аргументов загрузчика и симптомов устройства | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-repair-bootloader-arguments-and-device-symptoms-664481?course=rhce-enterprise-linux-practice-exam-02) |

#### Проблемы файловой системы, LVM, шифрования и iSCSI

|   Индекс | Название                                                                    | Сложность   | Практика                                                                                                                                                      |
|----------|-----------------------------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Восстановление монтирования поврежденного логического тома               | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-repair-a-broken-logical-volume-mount-664482?course=rhce-enterprise-linux-practice-exam-02)                   |
|        2 | 🎯  Восстановление данных из неправильно настроенного зашифрованного раздела | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-recover-data-from-a-misconfigured-encrypted-mount-664480?course=rhce-enterprise-linux-practice-exam-02)      |
|        3 | 🎯  Восстановление постоянного хранилища iSCSI после сбоя по емкости         | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-restore-persistent-iscsi-storage-after-capacity-outage-664485?course=rhce-enterprise-linux-practice-exam-02) |

#### Проблемы управления пакетами

|   Индекс | Название                                    | Сложность   | Практика                                                                                                                                  |
|----------|---------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Исправление неудачных транзакций пакетов | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-repair-failed-package-transactions-664483?course=rhce-enterprise-linux-practice-exam-02) |

#### Проблемы сетевого подключения

|   Индекс | Название                                               | Сложность   | Практика                                                                                                                                              |
|----------|--------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Исправление неисправного маршрута NetworkManager    | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-fix-a-broken-networkmanager-route-664479?course=rhce-enterprise-linux-practice-exam-02)              |
|        2 | 🎯  Диагностика конфликта привязки службы и брандмауэра | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-diagnose-firewall-and-service-binding-conflict-664478?course=rhce-enterprise-linux-practice-exam-02) |

#### Проблемы приложений, SELinux и контейнеризированных сред

|   Индекс | Название                                                | Сложность   | Практика                                                                                                                                                 |
|----------|---------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Отладка аварийно завершающегося процесса приложения  | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-debug-a-crashing-application-process-664477?course=rhce-enterprise-linux-practice-exam-02)              |
|        2 | 🎯  Восстановление службы Podman с ограничениями SELinux | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-restore-a-podman-service-with-selinux-constraints-664486?course=rhce-enterprise-linux-practice-exam-02) |

#### Проблемы аутентификации и идентификации

|   Индекс | Название                                                                       | Сложность   | Практика                                                                                                                                         |
|----------|--------------------------------------------------------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Исправление поиска идентификационных данных и поведения при входе в систему | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-repair-identity-lookup-and-login-behavior-664484?course=rhce-enterprise-linux-practice-exam-02) |

#### Анализ сбоев, SystemTap и сторонних данных диагностики

|   Индекс | Название                                                 | Сложность   | Практика                                                                                                                                        |
|----------|----------------------------------------------------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Создание безопасного диагностического зонда SystemTap | Начинающий  | [Начать Испытание](https://labex.io/ru/labs/rhel-create-a-safe-systemtap-diagnostic-probe-664476?course=rhce-enterprise-linux-practice-exam-02) |

## О LabEx

[LabEx](https://labex.io) - это интерактивная практическая обучающая платформа, посвященная программированию и технологиям. Она объединяет лаборатории, ИИ-помощь и виртуальные машины для обеспечения практического обучения без видео. Со строгим подходом 'Учись делая', интерактивными онлайн-средами в браузере с автоматизированными пошаговыми проверками, структурированной организацией контента с системой на основе Дерева Навыков, и растущим учебным ресурсом из 30 Деревьев Навыков и более 6,000 Лабораторий, [LabEx](https://labex.io) предлагает всестороннее практическое образование. Платформа включает ассистента обучения Labby, построенного на последних моделях ИИ, обеспечивающего разговорный опыт обучения.

