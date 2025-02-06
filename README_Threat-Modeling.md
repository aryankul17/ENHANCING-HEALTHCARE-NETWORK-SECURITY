# Threat Modeling

## **DREAD Model**
The **DREAD Model** evaluates cyber threats based on:
- **Damage Potential** – Impact on systems and data.
- **Reproducibility** – Ease of repeating the attack.
- **Exploitability** – Complexity of executing the attack.
- **Affected Users** – Number of impacted users.
- **Discoverability** – Ease of detecting the attack.

### **DREAD Scoring Example**
| Threat            | Damage | Reproducibility | Exploitability | Affected Users | Discoverability | Total Score |
|------------------|--------|----------------|---------------|----------------|----------------|--------------|
| Ransomware      | 10     | 8              | 9             | 10             | 5              | 42           |
| SQL Injection   | 7      | 9              | 8             | 9              | 9              | 42           |

---

## **STRIDE Model**
The **STRIDE Model** categorizes threats into:
- **Spoofing** – Identity theft or unauthorized access.
- **Tampering** – Modification of data or software.
- **Repudiation** – Lack of accountability for actions.
- **Information Disclosure** – Data leaks and breaches.
- **Denial of Service (DoS)** – Service disruptions.
- **Elevation of Privilege** – Unauthorized admin-level access.

### **STRIDE Example in Healthcare**
- **Spoofing:** Fake doctor credentials to access patient records.
- **Tampering:** Manipulation of **Electronic Health Records (EHRs)**.
- **Denial of Service:** DDoS attacks disrupting hospital operations.

Using **DREAD and STRIDE**, we assess security risks and implement **proactive defense mechanisms**.
