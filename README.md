# Awesome-Cloud-Powershell-Automation

# Awesome-Cloud-Powershell-Automation



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Cloud Infrastructure Management, Automation & Multi-Platform Cmdlets*  

**Last updated: October 2026**



This repository tracks notable **cloud provider modules** and **open-source PowerShell projects** for **Cloud PowerShell Automation**. These tools help developers and administrators manage cloud resources, virtual infrastructure, and enterprise systems directly from the PowerShell scripting environment.



**Examples** include Azure PowerShell Module, AWS Tools for PowerShell, Google Cloud Tools for PowerShell, VMware PowerCLI, Pure Storage PowerShell SDK, NetApp PowerShell Toolkit, Rubrik PowerShell Module, Veeam PowerShell, Cisco UCS PowerTool, and Nutanix Cmdlets (the category leaders).



**Open-source emphasis**: Cloud PowerShell automation has a **mature but provider-fragmented ecosystem**. **Azure PowerShell (Az)** and **AWS Tools for PowerShell** are both fully open-source and actively maintained, while **Google Cloud Tools for PowerShell** reached **deprecation in January 2026** and is no longer installable via the Google Cloud CLI . The most vibrant open-source activity is in **community-maintained modules** for **Proxmox VE** (Corsinvest and EldoBam modules) and **DSC resources** for Windows infrastructure . This section documents these solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ Provider Modules](#-provider-modules)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ Provider Modules



> **📊 Market Context**: Cloud PowerShell automation is **not a standalone commercial market** — cmdlet modules are **free value-adds** provided by cloud and infrastructure vendors to drive platform adoption. The broader cloud infrastructure management market is estimated at **~$18B in 2026**, with PowerShell remaining the dominant automation language for **Windows-centric enterprises and hybrid cloud environments**. The sector is **highly provider-concentrated** — Microsoft (Az), AWS (AWS.Tools), and VMware (PowerCLI) each ship their own first-party module as the primary programmatic interface. **Google Cloud Tools for PowerShell was deprecated in January 2026**, signaling Google's reduced investment in PowerShell tooling .



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Azure PowerShell (Az)](https://github.com/Azure/azure-powershell)** | **The most comprehensive cloud PowerShell module.** Contains cmdlets for developing, deploying, administering, and managing Microsoft Azure resources. Preinstalled in Azure Cloud Shell. The `Az` module replaces the legacy `AzureRM` module . | **Free** — module costs nothing. You pay for Azure resources consumed. | **Azure free account**: **$200 credit for 30 days** + **55+ always-free services** + 12 months of popular free services. **Az module**: Free to install from PowerShell Gallery . | **~$281B revenue (Microsoft FY2025)** |

| **[AWS Tools for PowerShell](https://github.com/aws/aws-tools-for-powershell)** | Manage AWS services from PowerShell. The **AWS.Tools** modular variant installs per-service modules (e.g., AWS.Tools.EC2, AWS.Tools.S3). Requires PowerShell 6+ or 5.1 with .NET Framework 4.7.2+ . | **Free** — modules cost nothing. You pay for AWS resources consumed. | **AWS Free Tier**: **$100 sign-up credits** + up to **$100 additional** through activities. **AWS.Tools.Installer** module simplifies installation and updates . | **~$638B revenue (Amazon FY2025)** |

| **[Google Cloud Tools for PowerShell](https://github.com/GoogleCloudPlatform/google-cloud-powershell)** | **Deprecated — do not use for new projects.** Contained PowerShell cmdlets for interacting with Google Cloud Platform. **Effective January 14, 2026, no longer installable via Google Cloud CLI** . | **N/A** — module deprecated. | **N/A** — migration to `gcloud` CLI recommended. | **~$350B revenue (Alphabet FY2025)** |

| **[VMware PowerCLI](https://developer.vmware.com/powercli)** | **The de facto standard for VMware automation.** PowerShell module for managing vSphere, vSAN, NSX-T, and VMware Cloud. Industry-standard for virtualization administrators. | **Free** — PowerCLI costs nothing. You pay for VMware/Broadcom licenses. | **PowerCLI**: Free to download and install. **VMware evaluation licenses**: 60-day trial for most products. | **Part of Broadcom (~$51B revenue)** |

| **[Pure Storage PowerShell SDK](https://github.com/PureStorage-OpenConnect/powershell-sdk)** | Manage Pure Storage FlashArray and FlashBlade from PowerShell. | **Free** — SDK costs nothing. You pay for Pure Storage hardware. | **Free SDK** from PowerShell Gallery. Hardware evaluation available on request. | **Private (~$2B+ revenue est.)** |

| **[NetApp PowerShell Toolkit](https://github.com/NetApp/netapp-powershell-toolkit)** | Manage NetApp ONTAP storage systems from PowerShell. | **Free** — toolkit costs nothing. You pay for NetApp hardware/licenses. | **Free toolkit** from NetApp support site. | **~$6B revenue (NetApp FY2025)** |

| **[Rubrik PowerShell Module](https://github.com/rubrikinc/rubrik-sdk-for-powershell)** | Automate Rubrik backup, recovery, and data security operations. | **Free** — module costs nothing. You pay for Rubrik platform. | **Free module**. **Rubrik trial**: Available on request for enterprise evaluation. | **$1.32B audited fiscal total (FY2026)** |

| **[Veeam PowerShell](https://github.com/VeeamHub/powershell)** | Automate Veeam Backup & Replication, Veeam ONE, and Veeam Cloud Connect. | **Free** — module costs nothing. You pay for Veeam licenses. | **Free module**. **Veeam Community Edition**: Free for up to 10 VMs. | **~$2.0B backup revenue** |

| **[Cisco UCS PowerTool](https://github.com/CiscoUcs/PowerTool)** | Manage Cisco UCS and Cisco Intersight infrastructure from PowerShell. | **Free** — tool costs nothing. You pay for Cisco hardware. | **Free PowerTool**. **UCS evaluation**: Available through Cisco partners. | **~$63B revenue (Cisco FY2025)** |

| **[Nutanix Cmdlets](https://github.com/nutanix/powershell)** | Manage Nutanix AHV, Prism Central, and Calm from PowerShell. | **Free** — cmdlets cost nothing. You pay for Nutanix licenses. | **Free cmdlets**. **Nutanix Community Edition**: Free for non-production use. | **Private (~$1.5B+ revenue est.)** |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |

|---|---|---|

| **[Azure PowerShell (Az)](https://github.com/Azure/azure-powershell)** — **Microsoft's official Azure PowerShell module.** Contains cmdlets for developing, deploying, administering, and managing Azure resources. The `Az` module replaces `AzureRM`. Preinstalled in Azure Cloud Shell. Compatible with PowerShell 7+ and Windows PowerShell 5.1 (with .NET Framework 4.7.2+) . Apache-2.0. | [![Stars](https://img.shields.io/github/stars/Azure/azure-powershell?style=social&color=white)](https://github.com/Azure/azure-powershell/stargazers) | ~4,500 |

| **[AWS Tools for PowerShell](https://github.com/aws/aws-tools-for-powershell)** — **AWS's official PowerShell module.** The `AWS.Tools` modular variant installs per-service modules (AWS.Tools.EC2, AWS.Tools.S3, etc.). The `AWS.Tools.Installer` module simplifies installation, updating, and removal. Requires PowerShell 6+ or 5.1 with .NET Framework 4.7.2+ . Apache-2.0. | [![Stars](https://img.shields.io/github/stars/aws/aws-tools-for-powershell?style=social&color=white)](https://github.com/aws/aws-tools-for-powershell/stargazers) | ~238 |

| **[Corsinvest Proxmox VE API](https://github.com/Corsinvest/cv4pve-api-powershell)** — **Proxmox VE PowerShell module for accessing the API like VMware PowerCLI.** Direct API access via `Invoke-PveRestApi`, indexed parameter support, task management, SPICE integration, VM operations by ID or name, monitoring, snapshots. Requires PowerShell 6.0+. Install from PowerShell Gallery: `Install-Module -Name Corsinvest.ProxmoxVE.Api` . | [![Stars](https://img.shields.io/github/stars/Corsinvest/cv4pve-api-powershell?style=social&color=white)](https://github.com/Corsinvest/cv4pve-api-powershell/stargazers) | ~250 |

| **[EldoBam Proxmox PVE Module](https://github.com/EldoBam/pve-powershell-module)** — **Proxmox VE PowerShell module.** API endpoint documentation included, `Initialize-PVE` for connection, token or credential authentication, `SkipCertificateCheck` option, Pester tests included (though noted as "currently useless") . | [![Stars](https://img.shields.io/github/stars/EldoBam/pve-powershell-module?style=social&color=white)](https://github.com/EldoBam/pve-powershell-module/stargazers) | ~50 |

| **[DSC Community](https://github.com/dsccommunity)** — **Community-maintained DSC resources for Windows infrastructure.** 92 repositories covering Hyper-V (`HyperVDsc`, 118 stars), DNS Server (`DnsServerDsc`, 65 stars), Security Policy (`SecurityPolicyDsc`, 179 stars), Exchange (`ExchangeDsc`, 81 stars), Web Administration (`WebAdministrationDsc`, 164 stars), and more . MIT. | [![DSC Community](https://img.shields.io/badge/DSC%20Community-92%20repos-blue)](https://github.com/dsccommunity) | ~1,500+ (across repos) |



**Additional open-source options worth exploring:**



| Repo | Description |

|---|---|

| **[AzOps](https://github.com/Azure/AzOps)** — PowerShell module that deploys (Push) ARM Resource Templates & Bicep files at all Azure scope levels and exports (Pull) ARM resource hierarchy. **382 stars** . | [![Stars](https://img.shields.io/github/stars/Azure/AzOps?style=social&color=white)](https://github.com/Azure/AzOps/stargazers) |

| **[AWS.Tools Install Script (HP-85/atp)](https://github.com/HP-85/atp)** — Multi-platform install script that downloads AWS.Tools.zip and extracts modules to user's PSModules folder. Parallel extraction on PowerShell 7+ completes full install in **~7 seconds** for 114 MB / 3,795 files . | [![Stars](https://img.shields.io/github/stars/HP-85/atp?style=social&color=white)](https://github.com/HP-85/atp/stargazers) |

| **[Azure Stack Hub Tools](https://github.com/Azure/AzureStack-Tools)** — PowerShell modules for managing and deploying resources to Azure Stack Hub. Includes CapacityManagement, Cloud capabilities, Resource Manager policy, registration, VPN connectivity, and Template validator . | [![Azure](https://img.shields.io/badge/Azure-Stack%20Hub-blue)](https://github.com/Azure/AzureStack-Tools) |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's a provider module or open-source project.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cloud PowerShell modules handle sensitive credentials and API keys; ensure proper secret management, least-privilege access, and compliance with organizational security policies.

- **Critical lifecycle notice**: **Google Cloud Tools for PowerShell was deprecated in January 2026**. Effective January 14, 2026, the module can no longer be installed using the Google Cloud CLI . Users should migrate to the `gcloud` CLI or other automation approaches.

- **Open-source reality**: Cloud PowerShell automation is **overwhelmingly open-source** — Azure PowerShell (Az), AWS Tools for PowerShell, and all provider modules listed here are **free, open-source tools** published by their respective vendors. The "Provider Modules" section documents first-party modules, while the "Open-Source GitHub Projects" section highlights community-maintained alternatives (Proxmox VE modules, DSC Community resources). **Every major cloud PowerShell module is free to download, use, and modify** — you pay only for the cloud resources you consume. The open-source path is **universally viable** for cloud PowerShell automation.

- **Pricing caveat**: All free tier figures above are **verified against cited search results** but may change without notice. Cloud provider free tiers often have eligibility restrictions (new accounts only), time limits, and service-specific quotas. Always check the provider's official page for current terms.



---



**Made for cloud administrators, DevOps engineers, platform teams, and Windows infrastructure specialists.**

Let's make cloud PowerShell automation more open, transparent, and accessible.
