# **RX_003 — CryptoWall (2014)**
*(SeedTools Ransomware History Exhibit — v1.0 Enterprise)*

## 🎯 Exhibit Purpose
RX‑003 presents the **global CryptoWall encryption incident of 2014**, which was one of the most destructive first-generation ransomware.
The exhibit demonstrates:

- evolution after CryptoLocker,
- transition to RSA‑2048 + AES‑256 encryption,
- aggressive spam campaigns and exploit kits,
- first mass use of botnets to distribute ransomware,
- deterministic CryptoWall encryption patterns.

CryptoWall was the **most profitable ransomware of 2014**—which is why it's the third exhibit in the SeedTools Exhibit.

--

## 🔵 1. Exhibit Details

```
Exhibit ID: RX‑003
Name: CryptoWall — Global Campaign
Year: 2014
Family: CryptoWall
Type: Historical Ransomware Incident
Status: Documented (No Artifact Attached)
```

---

## 🔵 2. Ransomware Extensions

CryptoWall used:

```
.encrypted
.decrypted_readme
```

and often left files **unchanged**, similar to CryptoLocker, but with more aggressive encryption.

---

## 🔵 3. Ransom note

Excerpt from the original message:

```
Your files have been encrypted!
To decrypt your files, you must pay the ransom.

Instructions are provided in DECRYPT_INSTRUCTION.html
```

Features:

- HTML + TXT + PNG (cross-platform instructions),
- professional layout,
- Bitcoin payment instructions,
- unique victim ID,
- links to Tor sites.

CryptoWall was the first ransomware that:

- used **Tor sites** for communication,
- generated **unique victim ID**,
- created **multiple versions of the ransom note** (HTML, TXT, PNG).

---

## 🔵 4. Directory structure after the incident

CryptoWall:

- encrypted files in-place,
- did not rename files,
- did not change directory structure,
- did not delete NTFS metadata,
- added instruction files to multiple directories.

Examples of encrypted file types:

### 📁 Documents
- DOCX
- XLSX
- PPTX
- PDF

### 📁 Photos
- JPG
- PNG
- TIFF

### 📁 Archives
- ZIP
- RAR
- 7Z

### 📁 Application Files
- DB
- PST
- program configurations

---

## 🔵 5. Deterministic Behavior of CryptoWall

CryptoWall demonstrates:

- deterministic RSA-2048 + AES-256 encryption scheme,
- deterministic file type selection,
- deterministic ransom note creation,
- deterministic communication with C2,
- deterministic infection method (exploit kits).

CryptoWall was the first ransomware that:

- used **malvertising** (malvertising),
- used **exploit kits** (e.g., Angler),

- infected systems without user interaction.

--

## 🔵 6. Technical Metadata

CryptoWall:

- preserved file dates,
- preserved file names,
- preserved directory structures,
- encrypted files in place,
- added instruction files to directories.

This makes it **more aggressive than CryptoLocker**, but still deterministic.

--

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

RX‑003 is:

- historical,
- global,
- aggressive,
- technical,
- deterministic,
- educational,
- key to the evolution of ransomware.

CryptoWall is the **third exhibit in the SeedTools Ransomware History Exhibit**—after CTB‑Locker (RX‑001) and CryptoLocker (RX‑002).

--
