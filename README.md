# MeliCERTes Project - knowledge base

![MeliCERTes logo](https://raw.githubusercontent.com/melicertes/docs/master/img/melicertes.png)

The knowledge base includes all the reference to software and components including in MeliCERTes.
As MeliCERTes CSP is composed of various projects, this repository gives an easy access to documentations
available for users, developers and contributors of the MeliCERTes CSP project.

# Overall philosophy

Cerebrate is the central component of the MeliCERTes eco-system, providing directory services, information sharing related meta information as well as orchestration services for the local tools it interconnects with. All of the local tool components of MeliCERTes are autonomous and can work without [Cerebrate](https://www.cerebrate-project.org/), with the latter providing services to facilitate the management and configuration of the connected tools. The architecture provides a high level of resilience without sacrificing each organisation's abilities to pick and choose the components they wish to run based on their specific needs.

## Cerebrate

|             |             |
| ----------- | ----------- |
| Official link      | [cerebrate](https://github.com/cerebrate-project/cerebrate)      |
| Description  | The Cerebrate Sync Platform core software. Cerebrate is an open-source platform meant to act as a trusted contact information provider and interconnection orchestrator for other security tools.  |
| Install Documentation | [INSTALL](https://github.com/cerebrate-project/cerebrate/blob/main/INSTALL/INSTALL.md) |
| Hardware Requirements | [Requirements](https://github.com/cerebrate-project/cerebrate/blob/main/README.md#requirements-and-installation) |
| User Documentation | |
| FAQ | |
| Issues | [Cerebrate Issues](https://github.com/cerebrate-project/cerebrate/issues) |
| Training materials | [Cerebrate Training Materials](https://github.com/cerebrate-project/cerebrate-training) |
| Virtual Image | |


## MISP

|             |             |
| ----------- | ----------- |
| Official link      | [MISP](https://www.misp-project.org/)      |
| Description  |  MISP (core software) - Open Source Threat Intelligence and Sharing Platform (formely known as Malware Information Sharing Platform)  |
| Install Documentation | [INSTALL](https://misp.github.io/MISP/) |
| Hardware Requirements | [Requirements](https://github.com/MISP/MISP/wiki/Frequently-Asked-Questions#2-what-are-the-hardware-requirements) |
| User Documentation | [misp-book](https://www.circl.lu/doc/misp/) |
| FAQ | [FAQ](https://github.com/MISP/MISP/wiki/Frequently-Asked-Questions) |
| Issues | [MISP Issues](https://github.com/MISP/MISP/issues) |
| Training materials | [MISP Training Materials](https://github.com/misp/misp-training) |
| Virtual Image | [MISP VM](https://www.circl.lu/misp-images/latest/) |
| Security Reporting and Issues| [security](https://www.misp-project.org/security/) |

## IntelMQ

|             |             |
| ----------- | ----------- |
| Official link      | [IntelMQ](https://github.com/certtools/intelmq)      |
| Description  |  IntelMQ is a solution for IT security teams for collecting and processing security feeds using a message queuing protocol.   |
| Install Documentation | https://intelmq.readthedocs.io/en/latest/user/installation.html |
| Hardware Requirements | [Requirements](https://intelmq.readthedocs.io/en/maintenance/user/hardware-requirements.html) |
| User Documentation | https://intelmq.readthedocs.io/en/latest/#user-guide |
| FAQ | https://intelmq.readthedocs.io/en/latest/user/FAQ.html |
| Issues | https://github.com/certtools/intelmq/issues |
| Training materials | https://github.com/certtools/intelmq-tutorial/ |
| Virtual Image |  |
| Security Reporting and Issues| [Security](https://github.com/certtools/intelmq/blob/master/SECURITY.md) |


## MWDB Core

|             |             |
| ----------- | ----------- |
| Official link | [MWDB Core](https://github.com/CERT-Polska/mwdb-core) |
| Description  | Malware repository component for automated malware collection/analysis systems.  |
| Install Documentation | https://mwdb.readthedocs.io/en/latest/setup-and-configuration.html |
| User Documentation | https://mwdb.readthedocs.io/en/latest/user-guide/index.html |
| FAQ | - |
| Issues | https://github.com/CERT-Polska/mwdb-core/issues |
| Training materials | https://www.first.org/events/training/ws-mar-apr2021/#pBuild-Your-Own-Malware-Analysis-Pipeline-Using-New-Open-Source-Tools |
| Virtual Image | - |
| Security Reporting and Issues | - |


## Karton

|             |             |
| ----------- | ----------- |
| Official link | [Karton](https://github.com/CERT-Polska/karton) |
| Description  | Distributed malware processing framework based on Python, Redis and MinIO.  |
| Install Documentation | https://karton-core.readthedocs.io/en/latest/getting_started.html |
| User Documentation | https://karton-core.readthedocs.io/ |
| FAQ | - |
| Issues | https://github.com/CERT-Polska/karton/issues |
| Training materials | https://www.first.org/events/training/ws-mar-apr2021/#pBuild-Your-Own-Malware-Analysis-Pipeline-Using-New-Open-Source-Tools |
| Virtual Image | - |
| Security Reporting and Issues | - |

## AIL Project

|             |             |
| ----------- | ----------- |
| Official link      | [AIL Project](https://www.ail-project.org/)      |
| Description  |  AIL Project is an open source framework composed of different modules to collect, crawl, dig and analyse unstructured data. AIL includes an extensible Python-based framework for analysis of unstructure information collected via an advanced Crawler manager (such as Tor hidden services) or from different feeders (such as Twitter, Discord, Telegram Stream providers) or custom feeders. |
| Install Documentation | [INSTALL](https://github.com/ail-project/ail-framework#installation) |
| Hardware Requirements |  |
| User Documentation |  |
| FAQ |  |
| Issues | [AIL Project issues](https://github.com/ail-project/ail-framework/issues) |
| Training materials | [AIL training materials](https://github.com/ail-project/ail-training) |
| Virtual Image | |
| Security Reporting and Issues| [security](https://github.com/ail-project/ail-framework/security/policy) |

## Taranis NG

|             |             |
| ----------- | ----------- |
| Official link      | [Taranis NG](https://www.taranis.ng/)      |
| Description  |  Taranis NG is an OSINT gathering and analysis tool for CSIRT teams and organisations. It allows osint gathering, analysis and reporting; team-to-team collaboration; and contains a user portal for simple self asset management. |
| Install Documentation | [INSTALL](https://github.com/SK-CERT/Taranis-NG/blob/main/docker/README.md) |
| Hardware Requirements | [Requirements](https://github.com/SK-CERT/Taranis-NG/blob/main/README.md#requirements) |
| User Documentation | - |
| FAQ | - |
| Issues | [Taranis NG issues](https://github.com/SK-CERT/Taranis-NG/issues) |
| Training materials | - |
| Virtual Image | - |
| Security Reporting and Issues| [security](https://github.com/SK-CERT/Taranis-NG/blob/main/SECURITY.md) |
