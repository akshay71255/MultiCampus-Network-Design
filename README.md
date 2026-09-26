# Multi-Campus Enterprise Network Infrastructure Design

An end-to-end Cisco Packet Tracer network simulation designed to support a multi-campus university environment with inter-building routing, VLAN segmentation, automated IP allocation, and cloud services integration.


## Network Architecture Overview

The topology connects two university campuses situated 20 miles apart via core routing devices:

* **Main Campus (3 Buildings):**
  * **Building A:** Management, HR, Finance (Admin Staff), and Faculty of Business.
  * **Building B:** Faculty of Engineering & Computing and Faculty of Art & Design.
  * **Building C:** IT Department, University Web Server, and Student Computer Labs.
* **Smaller Campus:**
  * **Faculty of Health & Sciences:** Staff offices and student labs segregated across separate floors.
* **External Cloud Services:** Hosted Email Server connected via static routing.


## Key Technical Features

* **VLAN & IP Subnetting:** Distinct IPv4 networks assigned per faculty and administrative department for complete traffic isolation.
* **Dynamic Routing (RIPv2):** Configured across all internal routers for dynamic reachability and convergence.
* **Static Routing:** Established for external cloud mail server connectivity.
* **Router-Based DHCP:** Automated dynamic IP address assignment for all Building A administrative devices.
* **Switching & Layer 2 Security:** VLAN trunking, access ports, and essential switch port security applied to access layer switches.
