# ENHANCING-CLOUD-DATA-SECURITY-AND-STORAGE-EFFICIENCY-THROUGH-DE-DUPLICATION-AND-AES

The motivation behind this project lies in addressing the dual challenge faced by cloud storage systems: optimizing storage space while maintaining strict security controls. The demand for secure cloud storage is rapidly increasing due to the growing reliance on cloud-based services for personal, organizational, and government data storage. Numerous real-world applications and scenarios emphasize the need for efficient deduplication combined with strong encryption:

Enterprise Data Management: Enterprises dealing with vast quantities of files for backups, archiving, and content sharing require storage solutions that are both secure and cost-effective.
Personal Cloud Storage: Users increasingly store personal data, including photos, documents, and videos, which often contain redundant files, increasing storage costs. Addressing these requirements necessitates a secure deduplication framework that incorporates modern encryption techniques like AES-256 and efficient hashing algorithms like SHA-256, ensuring both space optimization and uncompromised data security.
Objectives:

Implementing Block-Level Deduplication:
Splitting files into uniform 1KB blocks.
Generating SHA-256 hashes for each block.
Identifying and eliminating redundant blocks across multiple users.
Integrating AES-256 Encryptidas.
Encrypting only unique data blocks to reduce encryption overhead.
Dynamically generating secure encryption keys.
Protecting encrypted data blocks against unauthorized access.
Storing Data Securely in the Cloud:
Uploading encrypted blocks to a cloud storage service.
Ensuring metadata (hash values, block references, encryption keys) is securely maintained in a relational database.
User Authentication and Access Control:
Implementing secure login mechanisms.
Issuing unique secret keys for file download authorization.
Restricting access to authorized users only.
