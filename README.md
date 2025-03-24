# Azure-Route-Server
Azure Route Server High Availability Implementation & Troubleshooting

📌 Overview
This project demonstrates the implementation of Azure Route Server (ARS) to enable dynamic routing between Azure and on-premises networks via BGP, ensuring high availability and resilient hybrid connectivity in enterprise environments.

The primary use case involved configuring a redundant routing setup between Azure Virtual Network Gateways, SD-WAN appliances, and Azure Firewall while addressing route propagation issues, failover inconsistencies, and misconfigured BGP advertisements.

🎯 Objectives
Enable dynamic BGP route exchange between Azure and on-premises via Route Server

Integrate Azure Firewall with Route Server to support forced tunneling and traffic inspection

Ensure HA and resilience in routing paths during failover scenarios

Harden routing behavior and security posture

Document real-world troubleshooting for Azure Route Server deployments

🛠️ Key Components

<img width="542" alt="image" src="https://github.com/user-attachments/assets/f82de745-6762-474a-8063-9aa84c7e888b" />

What Was Implemented & Fixed
✅ Initial Setup
Deployed ARS into a dedicated subnet (RouteServerSubnet)

Configured peering with SD-WAN/NVA (BGP ASN, peer IPs)

Verified route advertisement and propagation to/from ARS

🪛 Troubleshooting & Fixes

<img width="545" alt="image" src="https://github.com/user-attachments/assets/5fa73d71-f6cc-4ed8-9cb7-1ae6434b3ab0" />

📈 Outcome
Achieved dynamic, resilient routing between on-premises and Azure

Improved route convergence time during failover

Enabled centralized inspection via Azure Firewall without losing routing flexibility

Hardened BGP and routing behavior to meet enterprise security standards

Delivered cost-optimized, automated routing without manual UDR maintenance

📚 Resources
Azure Route Server Docs: https://learn.microsoft.com/en-us/azure/route-server/overview

💬 Contact
Isaac Emeteveke
Cloud Architect • Azure Specialist & Security Specialist


