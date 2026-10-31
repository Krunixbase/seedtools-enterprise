# **SeedTools Ransomware Family Atlas v1.0**
*(SeedTools Enterprise — Ransomware Lineage & Family Mapping Module)*

## 🎯 Module Purpose
SeedTools Ransomware Family Atlas v1.0 is a **ransomware family lineage map**, showing:

- lineage,
- connections between families,
- technical eras (RSA → ECC → AES → Rust),
- operational models (spam → exploit kits → worm → RaaS → corporate ransomware),
- deterministic characteristics of each family,
- connections to RX Series exhibits.

Atlas is an analytical module that integrates:

- SeedTools Ransomware History Exhibit,
- SeedTools Encryption Timeline,
- SeedTools Forensic Gallery.

---

# **📚 Section 1 - Major Ransomware Families (2013–2024)**

Each family has a card:

```
Family: Name
Era: Year of Dominance
Model: Operational Technique
Algorithms: Encryption
Relations: Development Lines
Exhibit: RX-XXX
```

---

## **CryptoLocker (2013)**
- Era: Beginning of the Modern Ransomware Era
- Model: Asymmetric RSA Encryption
- Algorithms: RSA‑2048
- Relation: Precursor to CryptoWall
- Exhibit: RX_002

---

## **CryptoWall (2014)**
- Era: Professionalization of Encryption
- Model: Hybrid AES+ RSA
- Algorithms: AES‑256 + RSA‑2048
- Connections: CryptoLocker successor
- Exhibit: RX_003

---

## **CTB Locker (2015)**
- Epoch: ECC introduction
- Model: file encryption + extension change
- Algorithms: ECC
- Connections: unique line (ECC branch)
- Exhibit: RX_001

---

## **Locky (2016)**
- Epoch: mass spam campaigns
- Model: Word macros + Necurs botnet
- Algorithms: AES‑128 + RSA‑2048
- Connections: "spam → macros → botnet" line
- Exhibit: RX_004

---

## **WannaCry (2017)**
- Epoch: ransomware‑worm
- Model: EternalBlue exploit
- Algorithms: AES‑128 + RSA‑2048
- Links: "worm branch" line
- Exhibit: RX_005

---

## **Petya / NotPetya (2017)**
- Epoch: wipers disguised as ransomware
- Model: MBR overwrite + MFT destruction
- Algorithms: Salsa20
- Links: "wiper branch" line
- Exhibit: RX_006

---

## **REvil / Sodinokibi (2020)**
- Epoch: RaaS (Ransomware-as-a-Service)
- Model: double extortion
- Algorithms: AES‑256 + RSA‑2048
- Links: "modern RaaS branch"
- Exhibit: RX_007

---

## **Conti (2021)**
- Epoch: corporate ransomware
- Model: leak site + internal organization
- Algorithms: AES‑256 + RSA‑4096
- Links: "corporate branch"
- Exhibit: RX_008

---

## **BlackCat / ALPHV (2023)**
- Epoch: Rust‑based ransomware
- Model: triple extortion
- Algorithms: AES‑256 + ChaCha20 + RSA‑2048
- Connections: "Rust branch" line
- Exhibit: RX_009

---

## **LockBit (2024)**
- Epoch: automated RaaS
- Model: automation + partner ranking
- Algorithms: AES‑256 + RSA‑2048
- Connections: "automated RaaS branch" line
- Exhibit: RX_010

---

# **📊 Section 2 — Lineage Map**

### **1. RSA Lineage (2013–2016)**
CryptoLocker → CryptoWall → Locky
- Model: asymmetric encryption → hybrid
- Era: early professionalization

### **2. ECC Lineage (2015)**
CTB Locker
- Model: ECC as an alternative to RSA
- Era: experimental branch

### **3. Worm Lineage (2017)**
WannaCry
- Model: exploit → automated propagation
- Era: ransomware‑worm

### **4. Wiper Lineage (2017)**
Petya → NotPetya
- Model: data destruction
- Era: wiper masquerade

### **5. RaaS Lineage (2020–2024)**
REvil → Conti → BlackCat → LockBit
- Model: RaaS → corporate → Rust → automation
- Era: modern ransomware gangs

---

# **📘 Section 3 — Relationships with SeedTools Modules**

- SeedTools Ransomware History Exhibit
- SeedTools Encryption Timeline
- SeedTools Forensic Gallery
- SeedTools Security Model
- SeedTools Enterprise Architecture

---

# ⭐ Summary

SeedTools Ransomware Family Atlas v1.0 is:

- a complete lineage map of ransomware families,
- a deterministic analysis module,
- Enterprise Architecture compliant,
- linked to RX Series,

---
