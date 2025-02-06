# Network Security

## **Challenges**
- **Flat network architecture** allows **lateral movement** of attackers.
- Lack of **intrusion detection (IDS/IPS)** increases **silent breaches**.
- **Weak firewall configurations** expose sensitive data.

## **Solutions**
✅ **Network Segmentation** – Isolate patient data, research, and admin networks.  
✅ **Next-Gen Firewalls (NGFWs)** – Implement deep packet inspection.  
✅ **Intrusion Prevention Systems (IPS)** – Detect and block anomalies.  
✅ **Zero Trust Model** – Enforce strict access control policies.  
✅ **VPNs & Secure Remote Access** – Encrypt external connections.

## **Proposed Network Design**
- **DMZ Zone**: Web applications & patient portals.
- **HIPAA Compliance Zone**: Critical healthcare data storage.
- **Internal Network**: Admin & research facilities.
