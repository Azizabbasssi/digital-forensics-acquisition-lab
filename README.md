# 🔍 Digital Forensics Evidence Acquisition & Analysis Lab

A comprehensive digital forensics workflow demonstrating host-based data acquisition, cryptographic verification, and deep-dive artifact analysis to recover deleted file structures while maintaining strict evidentiary integrity.

📥 **Download Full Original Report:** [Digital_Forensics_Lab.docx](./Digital_Forensics_Lab.docx)

---

## 🔬 Core Investigative Workflows

### 1. Bit-Stream Evidence Ingestion
*   Utilized **FTK Imager** to generate a read-only, bit-stream forensic `.E01` image of the targeted storage media.
*   Preserved original storage parameters, isolating the target layout completely from host machine write operations to protect original data states.

### 2. Cryptographic Integrity Auditing
*   Generated and calculated data authentication signatures using **MD5 and SHA1** hashing algorithms at the exact moment of acquisition.
*   Executed post-analysis validation checks to guarantee zero-tamper integrity, matching source and destination blocks perfectly.

### 3. Automated Artifact Carving & Extraction
*   Ingested forensic images into the **Autopsy Digital Forensics** platform for systemic analysis.
*   Configured targeted file system parsing engines to search unallocated space, reconstruct fragmented header blocks, and carve out deleted master evidence files.

---

## 🧰 Forensic Toolkit Specs
*   **Analysis Platforms:** Autopsy Digital Forensics Framework
*   **Imaging Suites:** AccessData FTK Imager
*   **Validation Standards:** Cryptographic Hashing (MD5 / SHA1 Verification)
*   **Target Scope:** Data Recovery, Unallocated Cluster Carving, Chain of Custody Maintenance

---

## 📂 Repository File Blueprint
*   `Digital_Forensics_Lab.docx` — The original, comprehensive Word document detailing the full lab investigation.
*   `forensic_case_log.md` — Structural template mapping chronological analyst actions and cryptographic verification signatures.
*   `README.md` — Technical case documentation and environment analysis specifications.

---

## 🎯 Strategic Professional Impact
This project demonstrates operational readiness for Digital Forensics and Incident Response (DFIR) roles. It shows a deep practical knowledge of anti-tampering forensic principles, structural data validation, file system carving, and the precise logging required for enterprise threat investigation.
