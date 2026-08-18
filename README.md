# mini-isp
Multi-region ISP simulation featuring MPLS core, BNG functionality, L2VPN (xconnect), enterprise transport (BDO & BPI), and upstream NTT transit. (Work In Progress)
> ⚠️ **Project Status:** Active Development / In Progress

## Project Overview
This GNS3 lab simulates a regional Service Provider core network servicing three main regional POPs (Tarlac, Naga, and Makati). It models Broadband Network Gateway (BNG) subscriber management, MPLS core transport, and Layer 2 VPN enterprise services.

## Architecture & Hardware
* **Simulated Hardware:** Cisco vIOS Routers & Cisco c7200 Routers
* **Core Transport:** MPLS backbone using L2VPN (`xconnect` / Any Transport over MPLS)
* **Upstream Connectivity:** Simulated transit connection to an external NTT router
* **Enterprise Tenants:** Simulated L2/L3 transport for BDO Enterprise and BPI Enterprise

## Network Regions
* **TARLAC**,**NAGA**,**MAKATI** 

## Key Features & Configurations

### L2VPN / Any Transport over MPLS (xconnect)
Point-to-point Pseudowires are configured on customer-facing attachment circuits to extend Layer 2 domains across the MPLS core   
