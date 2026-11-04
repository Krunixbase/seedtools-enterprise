# **SeedTools Ransomware Vector Map v1.0**
*(SeedTools Enterprise — Attack Vector Mapping Module)*

## 🎯 Module Purpose
SeedTools Ransomware Vector Map v1.0 is a **map of ransomware attack vectors**, presenting:

- system entry techniques,
- infection methods,
- distribution channels,
- exploits,
- automatic propagation mechanisms,
- connections between ransomware families and their vectors,
- vector evolution from 2013 to 2024.

The module integrates:

- SeedTools Ransomware History Exhibit,
- SeedTools Encryption Timeline,
- SeedTools Ransomware Family Atlas,
- SeedTools Security Model.

---

# **📊 Section 1 - Main Ransomware Attack Vectors (2013–2024)**

Each vector has a tab:

```
Vector: Technique Name
Families: Ransomware Using the Technique
Era: Years of Dominance
Mechanism: How the Vector Works
Relationships: RX Series
```

---

## **1. Spam + Attachments (2013–2016)**
**Mechanism:**
- Emails with DOC, ZIP, EXE, PDF attachments,
- Social engineering (invoices, CVs, payment confirmations),
- User executes the attachment → infection.

**Families:**
- CryptoLocker
- CryptoWall
- Locky

**Associations:**
- RX_002
- RX_003
- RX_004

---

## **2. Word Macros (2016)**
**Mechanism:**
- DOCX document with macro,
- user clicks "Enable Content",
- macro downloads ransomware from C2.

**Families:**
- Locky

**Associations:**
- RX_004

---

## **3. Exploit Kits (2014–2017)**
**Mechanism:**
- malvertising,
- exploit kits (Angler, Neutrino),
- automatic exploitation of browser vulnerabilities.

**Families:**
- CryptoWall
- Locky

**Relationships:**
- RX_003
- RX_004

---

## **4. EternalBlue Worm / Exploit (2017)**
**Mechanism:**
- automatic network propagation,
- exploitation of the SMBv1 (MS17‑010) vulnerability,
- no user interaction.

**Families:**
- WannaCry
- NotPetya

**Relationships:**
- RX_005
- RX_006

---

## **5. Supply‑Chain Attack (2017)**
**Mechanism:**
- infection via software updates,
- infected update server,
- automatic malware download by victims.

**Families:**
- NotPetya

**Associations:**
- RX_006

---

## **6. RDP Brute‑Force (2018–2024)**
**Mechanism:**
- internet scanning,
- RDP password brute‑force,
- server takeover,
- manual ransomware deployment.

**Families:**
- REvil
- Conti
- LockBit

**Associations:**
- RX_007
- RX_008
- RX_010

---

## **7. Credential Theft (2020–2024)**
**Mechanism:**
- Password theft (Mimikatz, LSASS dump),
- Domain account takeover,
- Network-wide ransomware deployment.

**Families:**
- Conti
- LockBit
- BlackCat

**Affiliations:**
- RX_008
- RX_009
- RX_010

---

## **8. Zero‑Day Exploits (2021–2024)**
**Mechanism:**
- Exploitation of unknown vulnerabilities,
- Attacks on VPNs, firewalls, and email servers,
- Immediate infrastructure takeover.

**Families:**
- BlackCat
- LockBit

**Associations:**
- RX_009
- RX_010

---

## **9. RaaS Automation (2023–2024)**
**Mechanism:**
- automatic ransomware deployment,
- partner panel,
- ransom note generation,
- automatic encryption.

**Families:**
- BlackCat
- LockBit

**Associations:**
- RX_009
- RX_010

---

# **📌 Section 2 — Vector Matrix by Family**

| Family | Main Vector | Alternative Vectors |
|--------|---------------|-----------------------|
| **CryptoLocker** | Spam | Attachments |
| **CryptoWall** | Exploit Kits | Spam |
| **CTB Locker** | Spam | No alternatives |
| **Locky** | Word macros | Botnet Necurs |
| **WannaCry** | EternalBlue | Worm |
| **NotPetya** | Supply‑Chain | EternalBlue |
| **REvil** | RDP Brute-Force | Phishing |
| **Conti** | Credential Theft | RDP |
| **BlackCat** | Zero-Day | RDP, Automation |
| **LockBit** | Automation | RDP, Credential Theft |

---

# **📘 Section 3 — Relationships with SeedTools Modules**

- SeedTools Ransomware History Exhibit
- SeedTools Encryption Timeline
- SeedTools Ransomware Family Atlas
- SeedTools Security Model
- SeedTools Forensic Gallery

---

# ⭐ Summary

SeedTools Ransomware Vector Map v1.0 is:

- a complete map of ransomware attack vectors,
- a deterministic technical module,
- Enterprise Architecture-compliant,
- RX Series-related,
- ready for publication in the SeedTools Enterprise repo.

--
