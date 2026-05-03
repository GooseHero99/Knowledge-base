### Security+ Core: The CIA Triad

The CIA Triad is the foundational model guiding information security policies and architecture.

* **[C]onfidentiality:** Prevents unauthorized disclosure of information. Ensures data is only viewable by authorized entities. 
    * *Implementation:* Encryption (Data at rest/in transit), strict Access Controls (MFA, RBAC), Steganography.
* **[I]ntegrity:** Prevents unauthorized modification. Ensures data remains accurate, complete, and trustworthy.
    * *Implementation:* Hashing (SHA-256), Digital Signatures, Certificates.
* **[A]vailability:** Ensures systems, networks, and data are accessible to authorized users exactly when needed.
    * *Implementation:* Redundancy (RAID, HA clusters), Backups, Load Balancing, DDoS mitigation.

> **Note:** Effective security architecture requires continuous balancing of the Triad based on specific business needs. Over-prioritizing one pillar often creates friction with another; for example, extreme enforcement of Confidentiality can significantly degrade Availability and user experience.
