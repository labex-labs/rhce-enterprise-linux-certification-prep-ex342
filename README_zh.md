# RHCE in Enterprise Linux 培训 Certification Prep Path

## 支持语言

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/zh/learn/rhce-enterprise-linux"><img width="128px" src="https://file.labex.io/path/VJAk5cEITuZT.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/开始路径-whitesmoke?style=for-the-badge)](https://labex.io/zh/learn/rhce-enterprise-linux)

在 RHCSA（EX200）基础上，通过结构化的动手学习路径备考 Red Hat Certified Engineer in Enterprise Linux（EX342）考试。本路线图侧重高级 RHEL 诊断与故障排查、性能型考试任务与真实企业场景，涵盖证据收集、启动与内核、存储与 LVM、软件包、网络、应用与 SELinux、身份认证及崩溃调查等 EX342 主题。后续将逐步加入 RHCE in Enterprise Linux 课程、实验环境与模拟考试练习，帮助你建立与 EX342 目标一致的能力。

**课程**: 3 · **实验**: 56

## 课程

### 1. [RHCE 企业级 Linux 备考指南 (EX342)](https://labex.io/zh/courses/rhce-enterprise-linux-prep)

[![RHCE 企业级 Linux 备考指南 (EX342)](https://course-cover.labex.io/rhce-enterprise-linux-prep.png?lang=zh)](https://labex.io/zh/courses/rhce-enterprise-linux-prep)

本课程专为 RHCE 认证备考设计，包含 28 个引导式故障排查实验。内容涵盖从证据收集到系统引导、存储管理、软件包维护、网络配置、应用排查、身份验证以及高级调查等核心领域。

[开始课程](https://labex.io/zh/courses/rhce-enterprise-linux-prep) · 实验: 28

#### 故障排查方法与证据收集

|   序号 | 名称                        | 难度   | 练习                                                                                                                                |
|------|---------------------------|------|-----------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  收集事故基准证据               | 初级   | [开始实验](https://labex.io/zh/labs/collect-baseline-evidence-for-an-incident-664213?course=rhce-enterprise-linux-prep)               |
|    2 | 🧩  使用文档、日志和指标缩小根本原因范围     | 初级   | [开始实验](https://labex.io/zh/labs/use-documentation-logs-and-metrics-to-narrow-root-cause-664240?course=rhce-enterprise-linux-prep) |
|    3 | 🧩  配置集中式日志记录与 Journal 持久化 | 初级   | [开始实验](https://labex.io/zh/labs/configure-centralized-logging-and-journal-persistence-664216?course=rhce-enterprise-linux-prep)   |
|    4 | 🧩  使用 Web 控制台证据收集支持包      | 初级   | [开始实验](https://labex.io/zh/labs/gather-a-support-bundle-with-web-console-evidence-664223?course=rhce-enterprise-linux-prep)       |

#### 引导、服务、内核及硬件故障现象

|   序号 | 名称                     | 难度   | 练习                                                                                                                        |
|------|------------------------|------|---------------------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  诊断并修复启动服务故障         | 初级   | [开始实验](https://labex.io/zh/labs/diagnose-and-repair-a-failed-boot-service-664218?course=rhce-enterprise-linux-prep)       |
|    2 | 🧩  恢复 Root 访问权限并还原引导目标 | 初级   | [开始实验](https://labex.io/zh/labs/recover-root-access-and-restore-boot-target-664231?course=rhce-enterprise-linux-prep)     |
|    3 | 🧩  修复引导加载程序与内核参数漂移     | 初级   | [开始实验](https://labex.io/zh/labs/repair-bootloader-and-kernel-argument-drift-664234?course=rhce-enterprise-linux-prep)     |
|    4 | 🧩  检查硬件与设备故障信号         | 初级   | [开始实验](https://labex.io/zh/labs/inspect-hardware-and-device-failure-signals-664226?course=rhce-enterprise-linux-prep)     |
|    5 | 🧩  管理内核模块与持久化参数        | 初级   | [开始实验](https://labex.io/zh/labs/manage-kernel-modules-and-persistent-parameters-664228?course=rhce-enterprise-linux-prep) |

#### 存储恢复与持久化

|   序号 | 名称                   | 难度   | 练习                                                                                                                    |
|------|----------------------|------|-----------------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  恢复损坏的测试文件系统       | 初级   | [开始实验](https://labex.io/zh/labs/recover-a-corrupted-test-file-system-664229?course=rhce-enterprise-linux-prep)        |
|    2 | 🧩  修复 LVM 可见性与挂载状态   | 初级   | [开始实验](https://labex.io/zh/labs/repair-lvm-visibility-and-mount-state-664236?course=rhce-enterprise-linux-prep)       |
|    3 | 🧩  从加密卷中恢复数据         | 初级   | [开始实验](https://labex.io/zh/labs/recover-data-from-an-encrypted-volume-664230?course=rhce-enterprise-linux-prep)       |
|    4 | 🧩  诊断持久挂载与 UUID 问题   | 初级   | [开始实验](https://labex.io/zh/labs/diagnose-persistent-mount-and-uuid-problems-664221?course=rhce-enterprise-linux-prep) |
|    5 | 🧩  修复 iSCSI 发现与持久化登录 | 初级   | [开始实验](https://labex.io/zh/labs/repair-iscsi-discovery-and-persistent-login-664235?course=rhce-enterprise-linux-prep) |
|    6 | 🧩  解决存储空间耗尽问题        | 初级   | [开始实验](https://labex.io/zh/labs/resolve-storage-capacity-exhaustion-664239?course=rhce-enterprise-linux-prep)         |

#### 软件包与系统完整性

|   序号 | 名称                 | 难度   | 练习                                                                                                                         |
|------|--------------------|------|----------------------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  解决软件仓库与软件包依赖问题  | 初级   | [开始实验](https://labex.io/zh/labs/resolve-repository-and-package-dependency-issues-664238?course=rhce-enterprise-linux-prep) |
|    2 | 🧩  恢复 RPM 数据库与事务状态 | 初级   | [开始实验](https://labex.io/zh/labs/recover-rpm-database-and-transaction-state-664232?course=rhce-enterprise-linux-prep)       |
|    3 | 🧩  识别并恢复已更改的软件包文件  | 初级   | [开始实验](https://labex.io/zh/labs/identify-and-restore-changed-package-files-664224?course=rhce-enterprise-linux-prep)       |
|    4 | 🧩  诊断失败的更新与回滚操作    | 初级   | [开始实验](https://labex.io/zh/labs/diagnose-failed-updates-and-rollback-options-664219?course=rhce-enterprise-linux-prep)     |

#### 网络与应用程序故障

|   序号 | 名称                             | 难度   | 练习                                                                                                                          |
|------|--------------------------------|------|-----------------------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  修复 NetworkManager、DNS 和路由漂移 | 初级   | [开始实验](https://labex.io/zh/labs/repair-networkmanager-dns-and-routing-drift-664237?course=rhce-enterprise-linux-prep)       |
|    2 | 🧩  检查流量与防火墙服务路径                | 初级   | [开始实验](https://labex.io/zh/labs/inspect-traffic-and-firewall-service-paths-664227?course=rhce-enterprise-linux-prep)        |
|    3 | 🧩  识别应用程序库与运行时故障               | 初级   | [开始实验](https://labex.io/zh/labs/identify-application-library-and-runtime-failures-664225?course=rhce-enterprise-linux-prep) |
|    4 | 🧩  诊断 SELinux 应用拒绝访问问题         | 初级   | [开始实验](https://labex.io/zh/labs/diagnose-selinux-application-denials-664222?course=rhce-enterprise-linux-prep)              |
|    5 | 🧩  修复容器化应用服务                   | 初级   | [开始实验](https://labex.io/zh/labs/repair-a-containerized-application-service-664233?course=rhce-enterprise-linux-prep)        |

#### 身份验证与深度调查

|   序号 | 名称                       | 难度   | 练习                                                                                                                            |
|------|--------------------------|------|-------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  诊断 PAM 与身份查找故障        | 初级   | [开始实验](https://labex.io/zh/labs/diagnose-pam-and-identity-lookup-failures-664220?course=rhce-enterprise-linux-prep)           |
|    2 | 🧩  调试内存或进程级应用程序问题        | 初级   | [开始实验](https://labex.io/zh/labs/debug-a-memory-or-process-level-application-problem-664217?course=rhce-enterprise-linux-prep) |
|    3 | 🧩  收集内核崩溃转储证据            | 初级   | [开始实验](https://labex.io/zh/labs/collect-kernel-crash-dump-evidence-664214?course=rhce-enterprise-linux-prep)                  |
|    4 | 🧩  编译并检查安全的 SystemTap 探针 | 初级   | [开始实验](https://labex.io/zh/labs/compile-and-check-a-safe-systemtap-probe-664215?course=rhce-enterprise-linux-prep)            |

### 2. [RHCE 企业级 Linux 实战模拟考试 01](https://labex.io/zh/courses/rhce-enterprise-linux-practice-exam-01)

[![RHCE 企业级 Linux 实战模拟考试 01](https://course-cover.labex.io/rhce-enterprise-linux-practice-exam-01.png?lang=zh)](https://labex.io/zh/courses/rhce-enterprise-linux-practice-exam-01)

这是一场 RHCE 企业级 Linux 实战模拟考试，包含 14 个独立的 RHEL 故障排查案例，涵盖了证据收集、系统引导、存储管理、软件包管理、网络配置、应用程序、SELinux、容器、身份验证以及 SystemTap 等核心领域。

[开始课程](https://labex.io/zh/courses/rhce-enterprise-linux-practice-exam-01) · 实验: 14

#### 故障排查方法与证据收集

|   序号 | 名称                        | 难度   | 练习                                                                                                                                             |
|------|---------------------------|------|------------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  收集受损主机的证据              | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-collect-evidence-for-a-degraded-host-664461?course=rhce-enterprise-linux-practice-exam-01)                |
|    2 | 🎯  恢复集中式日志记录与 Journal 持久化 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-restore-centralized-logging-and-journal-persistence-664471?course=rhce-enterprise-linux-practice-exam-01) |

#### 启动、引导、硬件及内核问题

|   序号 | 名称                   | 难度   | 练习                                                                                                                                                 |
|------|----------------------|------|----------------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复启动服务依赖故障        | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-repair-a-failed-boot-service-dependency-664466?course=rhce-enterprise-linux-practice-exam-01)                 |
|    2 | 🎯  修复内核或引导配置漂移后的访问权限 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-restore-access-after-kernel-or-boot-configuration-drift-664470?course=rhce-enterprise-linux-practice-exam-01) |

#### 文件系统、LVM、加密及 iSCSI 问题

|   序号 | 名称                  | 难度   | 练习                                                                                                                                         |
|------|---------------------|------|--------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  恢复损坏的文件系统及挂载状态   | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-recover-a-corrupted-file-system-and-mount-state-664465?course=rhce-enterprise-linux-practice-exam-01) |
|    2 | 🎯  修复不完整的 LVM 堆栈    | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-repair-an-incomplete-lvm-stack-664467?course=rhce-enterprise-linux-practice-exam-01)                  |
|    3 | 🎯  恢复加密的 iSCSI 存储访问 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-restore-encrypted-iscsi-storage-access-664472?course=rhce-enterprise-linux-practice-exam-01)          |

#### 软件包管理问题

|   序号 | 名称               | 难度   | 练习                                                                                                                                          |
|------|------------------|------|---------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  解决软件包数据库与依赖故障 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-resolve-package-database-and-dependency-failures-664468?course=rhce-enterprise-linux-practice-exam-01) |

#### 网络连接问题

|   序号 | 名称             | 难度   | 练习                                                                                                                                        |
|------|----------------|------|-------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  恢复网络服务可达性   | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-restore-network-service-reachability-664473?course=rhce-enterprise-linux-practice-exam-01)           |
|    2 | 🎯  捕获路由问题的流量证据 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-capture-traffic-evidence-for-a-routing-problem-664460?course=rhce-enterprise-linux-practice-exam-01) |

#### 应用程序、SELinux 及容器化应用问题

|   序号 | 名称                     | 难度   | 练习                                                                                                                                           |
|------|------------------------|------|----------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复应用程序依赖与运行时故障      | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-fix-an-application-dependency-and-runtime-failure-664462?course=rhce-enterprise-linux-practice-exam-01) |
|    2 | 🎯  解决 SELinux 与容器化服务故障 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-resolve-selinux-and-containerized-service-failure-664469?course=rhce-enterprise-linux-practice-exam-01) |

#### 身份验证与身份识别问题

|   序号 | 名称             | 难度   | 练习                                                                                                                 |
|------|----------------|------|--------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复 PAM 登录失败 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-fix-a-pam-login-failure-664463?course=rhce-enterprise-linux-practice-exam-01) |

#### 系统崩溃、SystemTap 及第三方调查数据

|   序号 | 名称                      | 难度   | 练习                                                                                                                                       |
|------|-------------------------|------|------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  收集崩溃与 SystemTap 调查数据 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-gather-crash-and-systemtap-investigation-data-664464?course=rhce-enterprise-linux-practice-exam-01) |

### 3. [RHCE 企业级 Linux 实战模拟考试 02](https://labex.io/zh/courses/rhce-enterprise-linux-practice-exam-02)

[![RHCE 企业级 Linux 实战模拟考试 02](https://course-cover.labex.io/rhce-enterprise-linux-practice-exam-02.png?lang=zh)](https://labex.io/zh/courses/rhce-enterprise-linux-practice-exam-02)

这是第二套 RHCE 企业级 Linux 实战模拟考试，包含 14 个独立的 RHEL 故障排查案例，涵盖证据收集、系统引导、存储管理、软件包、网络配置、应用程序、SELinux、容器、身份验证以及 SystemTap 等核心领域。

[开始课程](https://labex.io/zh/courses/rhce-enterprise-linux-practice-exam-02) · 实验: 14

#### 故障排查方法与证据收集

|   序号 | 名称             | 难度   | 练习                                                                                                                                        |
|------|----------------|------|-------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  为重复性故障构建支持包 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-build-a-support-bundle-for-a-recurring-failure-664474?course=rhce-enterprise-linux-practice-exam-02) |
|    2 | 🎯  配置带日志的诊断收集  | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-configure-diagnostic-collection-with-logging-664475?course=rhce-enterprise-linux-practice-exam-02)   |

#### 启动、引导、硬件及内核问题

|   序号 | 名称                 | 难度   | 练习                                                                                                                                         |
|------|--------------------|------|--------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  恢复陷入紧急模式的系统     | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-restore-a-system-stuck-in-emergency-mode-664487?course=rhce-enterprise-linux-practice-exam-02)        |
|    2 | 🎯  修复引导加载程序参数与设备故障 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-repair-bootloader-arguments-and-device-symptoms-664481?course=rhce-enterprise-linux-practice-exam-02) |

#### 文件系统、LVM、加密及 iSCSI 问题

|   序号 | 名称                      | 难度   | 练习                                                                                                                                                |
|------|-------------------------|------|---------------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复损坏的逻辑卷挂载           | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-repair-a-broken-logical-volume-mount-664482?course=rhce-enterprise-linux-practice-exam-02)                   |
|    2 | 🎯  恢复配置错误的加密挂载数据        | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-recover-data-from-a-misconfigured-encrypted-mount-664480?course=rhce-enterprise-linux-practice-exam-02)      |
|    3 | 🎯  在容量故障后恢复持久化 iSCSI 存储 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-restore-persistent-iscsi-storage-after-capacity-outage-664485?course=rhce-enterprise-linux-practice-exam-02) |

#### 软件包管理问题

|   序号 | 名称            | 难度   | 练习                                                                                                                            |
|------|---------------|------|-------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复失败的软件包事务 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-repair-failed-package-transactions-664483?course=rhce-enterprise-linux-practice-exam-02) |

#### 网络连接问题

|   序号 | 名称                         | 难度   | 练习                                                                                                                                        |
|------|----------------------------|------|-------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复损坏的 NetworkManager 路由 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-fix-a-broken-networkmanager-route-664479?course=rhce-enterprise-linux-practice-exam-02)              |
|    2 | 🎯  诊断防火墙与服务绑定冲突            | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-diagnose-firewall-and-service-binding-conflict-664478?course=rhce-enterprise-linux-practice-exam-02) |

#### 应用程序、SELinux 及容器化应用问题

|   序号 | 名称                            | 难度   | 练习                                                                                                                                           |
|------|-------------------------------|------|----------------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  调试崩溃的应用程序进程                | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-debug-a-crashing-application-process-664477?course=rhce-enterprise-linux-practice-exam-02)              |
|    2 | 🎯  恢复带有 SELinux 约束的 Podman 服务 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-restore-a-podman-service-with-selinux-constraints-664486?course=rhce-enterprise-linux-practice-exam-02) |

#### 身份认证与鉴权问题

|   序号 | 名称             | 难度   | 练习                                                                                                                                   |
|------|----------------|------|--------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复身份查找与登录行为 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-repair-identity-lookup-and-login-behavior-664484?course=rhce-enterprise-linux-practice-exam-02) |

#### 系统崩溃、SystemTap 及第三方调查数据

|   序号 | 名称                      | 难度   | 练习                                                                                                                                  |
|------|-------------------------|------|-------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  创建安全的 SystemTap 诊断探针 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-create-a-safe-systemtap-diagnostic-probe-664476?course=rhce-enterprise-linux-practice-exam-02) |

## 关于 LabEx

[LabEx](https://labex.io) 是一个专注于编程和技术的交互式动手学习平台。它结合了实验室、AI 辅助和虚拟机，提供无视频的实践学习体验。采用严格的'边学边做'方法，浏览器内的交互式在线环境具有自动化的逐步检查，基于技能树的结构化内容组织系统，以及不断增长的学习资源（包含 30 个技能树和超过 6,000 个实验），[LabEx](https://labex.io) 提供全面的实践教育。该平台包含基于最新 AI 模型构建的学习助手 Labby，提供对话式学习体验。

