---
title: Hardware and Software Requirements
keywords: hardware requirements
sidebar: sumadoc-31_sidebar
permalink: gs-hardware-and-software-requirements.html
folder: suse-mgr3.1/getting-started/first-steps
toc: true
---


## Hardware Requirements {#hardware-requirements}

Review the following table for SUSE Manager hardware and software requirements.

| Hardware | Recommended |
| --- | ---                                                               |
| CPU             | Multi-core 64-bit CPU `x86_64, ppc64le`               |
| RAM             | Minimum 4GB+ for test server                          |
| Free Disk Space | Minimum 100GB for root partition                      |
|                 | Minimum 50GB for database: `/var/lib/pgsql`                     |
|                 | Minimum 50GB per SUSE product synced to: `/var/spacewalk`    |
|                 | Minimum 200GB per Red Hat product synced to: `var/spacewalk` |


## SUSE Manager Base OS {#base-host-os}
Currently SUSE Manager 3.1 Server is based on the following host OS.

| Base OS | SUSE Manager Version |
| --- | --- |
| SLES 12 SP3 | 3.0, 3.1 |


## SUSE Supported Client Systems {#supported-client-systems}

Clients with the following operating systems are supported for registration with SUSE Manager. If you wish to use the latest Salt features, ensure your clients are supported.


{% include important.html content="Client operating system versions and SP levels must be under general support (normal or LTSS) to be supported with SUSE Manager. See: [Product Support Lifecycle](https://www.suse.com/lifecycle)." %}


| Operating Systems | Architecture | Traditional Clients | Salt Clients |
| --- | --- | --- | --- |
| SUSE Linux Enterprise 11 SP4 LTSS | `x86, x86_64, Itanium, ppc64le, zSystems` | Supported | Supported |
| SUSE Linux Enterprise 12 SP1, SP2, SP3 | `x86_64, ppc64le, zSystems` | Supported | Supported |
| Red Hat Enterprise Linux 5 | `x86, x86_64` | Supported | `Unsupported` |
| Red Hat Enterprise Linux 6 | `x86, x86_64` | Supported | Supported |
| Red Hat Enterprise Linux 7 | `x86, x86_64` | Supported | Supported |
| Novell Open Enterprise Server 11, SP1, SP2, SP3 LTSS | `x86, x86_64` | Supported | Supported |

