# **RX_002 — CryptoLocker (2013)**
*(SeedTools Ransomware History Exhibit — v1.0 Enterprise)*

## 🎯 Exhibit Purpose
RX-002 depicts the **historical CryptoLocker encryption incident from 2013**, which ushered in the global era of modern ransomware.
The exhibit demonstrates:

- the first mass use of RSA-2048 encryption,
- the first global email campaigns with ZIP/EXE attachments,
- the first "professional" ransom notes,
- the first cases of complete data loss without backups,
- the deterministic encryption patterns used by CryptoLocker.

CryptoLocker is a **foundation of ransomware history** — which is why it is the second exhibit in the SeedTools Exhibit.

---

## 🔵 1. Exhibit Data

```
Exhibit ID: RX‑002
Name: CryptoLocker — Global Outbreak
Year: 2013
Family: CryptoLocker
Type: Historical Ransomware Incident
Status: Documented (No Artifact Attached)
```

*(CryptoLocker is a historical incident—it doesn't have a physical FA artifact like CTB‑Locker, but its behavior is fully documented.)*

---

## 🔵 2. Ransomware Extensions

CryptoLocker used:

```
.bricked
.locked
.encrypted
```

and left encrypted files **without changing the extension**, which was characteristic of the first generation of ransomware.

---

## 🔵 3. Ransom note

Excerpt from the original message:

```
Your personal files are encrypted.
RSA-2048 encryption has been used.
To decrypt your files, you must pay the ransom.
```

Characteristics:

- professional,
- technical,
- written in English,
- contained Bitcoin payment instructions,
- included a timer (72 hours).

CryptoLocker was the first ransomware to use **Bitcoin** as a payment method.

--

## 🔵 4. Directory structure after the incident

CryptoLocker:

- did not change file names,
- did not change extensions (frequently),
- did not change directory structure,
- did not delete NTFS metadata,
- encrypted files in-place.

Examples of encrypted file types:

### 📁 Documents
- DOC
- XLS
- PPT
- PDF

### 📁 Photos
- JPG
- PNG
- BMP

### 📁 Archives
- ZIP
- RAR

### 📁 Application files
- DB
- PST
- program configurations

---

## 🔵 5. Deterministic Behavior of CryptoLocker

CryptoLocker demonstrates:

- deterministic RSA-2048 encryption scheme,
- deterministic file type selection,
- deterministic method of creating ransom notes,
- deterministic method of blocking access to the system,
- deterministic method of communicating with the C2 (Command & Control).

CryptoLocker was the first ransomware that:

- used **strong asymmetric encryption**,
- used **a unique key for each device**,
- used **C2 servers to generate keys**,
- locked the system using a ransom note window.

--

## 🔵 6. Technical Metadata

CryptoLocker:

- preserved file dates,
- preserved file names,
- preserved directory structure,
- encrypted files in place (no copies),
- left no additional NTFS metadata.

This makes it a **pure, deterministic encryption method**.

---

## 🔵 7. Exhibit Presentation Rules

### Allowed:
- file type names,
- ransomware extensions,
- ransom note fragments,
- directory structures,
- technical metadata,
- malware behavior.

### Prohibited:
- private photos,
- private documents,
- personal data.

--

## ⭐ Summary

RX‑002 is:

- historical,
- global,
- technical,
- deterministic,
- educational,
- fundamental to ransomware development.

CryptoLocker is the **second exhibit in the SeedTools Ransomware History Exhibit**—after CTB‑Locker (RX‑001).

--
