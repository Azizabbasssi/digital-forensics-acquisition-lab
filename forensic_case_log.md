# 🔍 Forensic Case Log & Chain of Custody Template

### 📁 Case Overview
* **Case Reference:** CASE-2026-001
* **Lead Examiner:** Abdul Aziz Abbasi
* **Investigation Objective:** Live data acquisition, cryptographic validation, and data carving from targeted storage volumes.

---

### 🔏 Chain of Custody Log
| Date/Time | Action Performed | Witness/Custodian | Verification Hash (MD5/SHA1) |
| :--- | :--- | :--- | :--- |
| 2026-06-06 | Evidence Image Acquisition via FTK Imager | Lab Custodian | `5d41402abc4b2a76b9719d911017c592` |
| 2026-06-06 | Ingestion into Autopsy Case Framework | Lead Examiner | `5d41402abc4b2a76b9719d911017c592` |
| 2026-06-06 | Metadata Extraction & File Carving | Lead Examiner | `MATCHED - INTEGRITY VERIFIED` |

---

### 🔬 Analysis Steps Completed
1. **Bit-Stream Copy:** Generated a forensic `.E01` evidence image of the media volume using **FTK Imager** to ensure read-only protection.
2. **Hash Verification:** Calculated original acquisition hashes to compare against post-analysis datasets, ensuring absolute zero-tamper evidence validation.
3. **Keyword Search & Data Carving:** Configured **Autopsy** ingest modules to locate unallocated clusters, reconstruct deleted document headers, and extract target artifacts.
