# HTPv1 Protocol (Hash-Timestamp-Proof v1)

**A cryptographically secure protocol for document integrity verification, timestamping, and digital signing.**

---

## US English Version

### 📖 About
The **HTPv1 Protocol** is a standardized workflow for proving the existence, integrity, and authorship of a digital document at a specific point in time. It combines local cryptographic hashing, decentralized storage (IPFS), blockchain anchoring, and PGP digital signatures to create a tamper-evident and independently verifiable record.

### ⚙️ Algorithm & Workflow
The protocol follows a strict, reproducible sequence of steps:

1. **Key Fingerprint**: Extract the Public Key Fingerprint of the signer.
2. **Hashing**: Calculate the `SHA-256` hash of the original, untouched document (e.g., `HTPv1.docx`).
3. **Decentralized Storage**: Upload the original document to **IPFS** to obtain a permanent Content Identifier (`IPFS CID`).
4. **Blockchain Anchoring**: Record the document hash and/or IPFS CID in a **Blockchain** or via **OpenTimestamps** to create an immutable, time-stamped proof (`Blockchain Anchor`).
5. **Metadata Generation**: Create a fixed text file (`HTPv1_fixed.txt`) containing:
   - Public Key Fingerprint
   - Document Hash (SHA-256)
   - IPFS CID
   - Blockchain Anchor (Transaction ID / Block Number)
6. **Digital Signature**: Cryptographically sign the `HTPv1_fixed.txt` file using **PGP** (e.g., via *Kleopatra* on Windows) to generate the final `.sig` signature file.

> **Note:** The original document (`HTPv1.docx`) remains completely unmodified throughout this process.

### 📂 Repository Structure
Protocol_HTP/
├── README.md # This file
├── Algoritm.txt # Raw algorithm description
├── En_version/ # English documentation and specifications
├── Ru_version/ # Russian documentation and specifications
├── Mn_version/ # Mongolian documentation and specifications
├── HTPv1_EN_fixed.docx # Example of a finalized English document
├── HTPv1_RU_fixed.docx # Example of a finalized Russian document
└── Document-HTPv1-Timestamp-Signature.zip # Archived reference materials