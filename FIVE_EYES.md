This document compiles publicly available cybersecurity guidelines from Five Eyes member countries that correspond to U.S. security controls. It is intended for cross-reference and educational purposes only.

# The Five Eyes (5-Eyes) Intelligence Alliance
The **Five Eyes** is an intelligence alliance comprising five English-speaking countries that share intelligence and cooperate closely on national security matters.  

**Member Countries:**
- **United States (US)**
- **United Kingdom (UK)**
- **Canada**
- **Australia**
- **New Zealand**

The **Five Eyes** is one of the most powerful intelligence-sharing partnerships in the world, focused on signals intelligence, cybersecurity, and high-level national security collaboration.

## Origins
- The alliance traces back to **World War II** and was formalized with the **UKUSA Agreement** in 1946.  
- Originally established to share **signals intelligence (SIGINT)** collected through cryptography and electronic surveillance.

**Timeline**
* 1939 to 1945 - World War II begins. The United States and the United Kingdom begin deep cooperation in signals intelligence, codebreaking, and cryptanalysis. Joint efforts on breaking German and Japanese codes form the foundation of later SIGINT sharing.
* 1940 - The British and Americans begin sharing cryptographic results informally as part of wartime necessity, including work at Bletchley Park and American cryptologic units.
* 1941 - The Atlantic Charter and the overall wartime alliance further strengthen intelligence sharing between the U.S. and U.K.
* 1943 - The BRUSA Agreement is signed. This is one of the earliest formal arrangements between the U.S. and the U.K. to share signals intelligence. It lays structural groundwork for future cooperation.

* 1946 - The UKUSA Agreement is signed. This is the major post-war formal agreement that defines long-term SIGINT cooperation between the United States and the United Kingdom. It becomes the backbone of what eventually becomes the Five Eyes alliance.
* 1948 - Canada formally joins the UKUSA intelligence arrangement. Canada becomes the third member of what will later be called the Five Eyes.
* 1953 - Australia and New Zealand officially join the UKUSA structure. This completes the five-nation intelligence-sharing relationship: United States, United Kingdom, Canada, Australia, and New Zealand.
* 1950s - The term “Five Eyes” begins to circulate internally within intelligence and diplomatic communities. The phrase comes from classification markings such as “AUS/CAN/NZ/UK/US EYES ONLY,” which was shortened colloquially to “Five Eyes.”
* 1960s to 1980s - Five Eyes builds a global SIGINT network during the Cold War, including cooperative global listening posts, satellite interception systems, and coordinated cryptologic operations.
* 1990s - Five Eyes adapts from Cold War military intelligence to emerging cyber and communications intelligence. Secure digital networks across member countries strengthen SIGINT sharing.
* 2000s - Counterterrorism drives deeper integration of Five Eyes surveillance and data-sharing systems. Joint operations and shared threat intelligence expand.
* 2013 - Public leaks expose some of the internal structure and operations of Five Eyes, confirming cooperation in global communications monitoring.
* 2010s to 2020s - Five Eyes continues to operate as one of the world’s closest intelligence partnerships. Cooperation expands to cybersecurity, counter-espionage, and critical-infrastructure protection. The alliance becomes increasingly important in cyber threats, encryption debates, and global intelligence coordination.


## Purpose
- **Signals Intelligence (SIGINT):** Collecting and sharing communications, electronic signals, and other intelligence.  
- **Counterterrorism and Counterespionage:** Joint operations and intelligence sharing to identify threats.  
- **Cybersecurity Collaboration:** Monitoring cyber threats and securing critical infrastructure.

## How it Works
- Each country collects intelligence within its own jurisdiction.  
- Intelligence is **shared with all Five Eyes members**, giving them global coverage that would be difficult to achieve individually.  
- Members coordinate on analysis, operations, and policy.

## Secrecy and Scope
- The alliance is **highly secretive**.  
- Focus is primarily on **foreign intelligence**, though some domestic surveillance controversies exist.  
- Five Eyes sometimes collaborates with other countries through “second-tier” partnerships, such as **Nine Eyes** or **Fourteen Eyes**, expanding the intelligence-sharing network.

---
# UNITED KINGDOM

Key UK Cybersecurity Standards & Publications (NCSC, Cabinet Office, Cyber Essentials)

This secction lists the most widely used and foundational **United Kingdom
government cybersecurity publications**, including guidance from the **National Cyber Security Centre (NCSC)**, **Cabinet Office**, **CESG**,  
**Cyber Essentials**, cryptographic standards, cloud security guidance,  and assurance frameworks.

All links go to official UK government** domains.

## 🇬🇧 Main Resource Libraries
* NCSC Guidance Library - https://www.ncsc.gov.uk/collection/all-topics
* UK Government Cyber Security Guidance (GOV.UK) - https://www.gov.uk/topic/technology/cyber-security


## 🧩 Governance, Assurance & National Frameworks
* Cyber Assessment Framework (CAF) - https://www.ncsc.gov.uk/collection/caf
* Government Functional Standard for Security (GovS 007) - https://www.gov.uk/government/publications/government-functional-standard-govs-007-security
* Minimum Cyber Security Standard (MCSS) - https://www.gov.uk/government/publications/minimum-cyber-security-standard
* Security Policy Framework (SPF) – Cabinet Office - https://www.gov.uk/government/collections/security-policy-framework
* Public Sector Network (PSN) Compliance - https://www.gov.uk/guidance/public-services-network-psn-compliance

## 🏛️ Protection of Government & Critical Services
* NCSC – Security for Government IT and Services - https://www.ncsc.gov.uk/collection/government-it
* Critical National Infrastructure (CNI) Security Guidance - https://www.ncsc.gov.uk/section/critical-national-infrastructure/introduction
* Defence Cyber Protection Partnership (DCPP) - https://www.gov.uk/guidance/defence-cyber-protection-partnership

## 🛡️ Cyber Essentials & Certifications
* Cyber Essentials - https://www.cyberessentials.ncsc.gov.uk/
* Cyber Essentials Plus - https://www.ncsc.gov.uk/cyber-essentials/overview
* IASME Governance Standard - https://iasme.co.uk/iasme-governance-standard/

## 🔒 Cryptography (UK / NCSC)
* NCSC Cryptographic Guidance Hub - https://www.ncsc.gov.uk/collection/cryptography
* NCSC – Using Cryptography in Government - https://www.ncsc.gov.uk/guidance/using-cryptography-in-government
* NCSC-Approved Cryptographic Algorithms & Protocols - https://www.ncsc.gov.uk/collection/cryptography-and-certificates/approved-algorithms
* Key Management Guidance (NCSC) - https://www.ncsc.gov.uk/collection/cryptography/key-management

* ⚛️ Post-Quantum Cryptography (UK Guidance)
> Note: The UK aligns with NIST PQC selections but provides UK-specific adoption guidance.

* NCSC – Post-Quantum Cryptography Overview - https://www.ncsc.gov.uk/whitepaper/protecting-the-future-quantum-safe-cryptography
* NCSC – Preparing for Post-Quantum Migration - https://www.ncsc.gov.uk/guidance/preparing-for-pqc-migration

## ☁️ Cloud Security & Assurance
* NCSC Cloud Security Guidance (14 Principles) - https://www.ncsc.gov.uk/collection/cloud-security
* NCSC Guidance for Secure Cloud Adoption - https://www.ncsc.gov.uk/guidance/cloud-adoption

---
# CANADA

Canada publishes very clear public guidance on which hash functions are approved.

The key document is:

“Cryptographic algorithms for UNCLASSIFIED, PROTECTED A, and PROTECTED B information – ITSP.40.111” from the Canadian Centre for Cyber Security.

In that document, the section on secure hash algorithms (or hash functions, depending on the version) explicitly says:
	1.	SHA-1 is no longer recommended except in very limited legacy contexts. It must not be used for digital signatures or any application requiring collision resistance. It should be phased out even for HMAC, KDFs, and RNGs.
	2.	SHA-2 (SHA-224, SHA-256, SHA-384, SHA-512, SHA-512/224, SHA-512/256) is recommended for digital signatures, HMACs, KDFs, and random bit generators. SHA-224 should be phased out by the end of 2030.
	3.	SHA-3 (SHA3-224, SHA3-256, SHA3-384, SHA3-512) is also recommended for the same uses (digital signatures, HMACs, KDFs, and RNGs). SHA3-224 should be phased out by the end of 2030.

So for Canada:
	•	SHA-2 and SHA-3 families are explicitly recommended.
	•	SHA-1 is being phased out and prohibited for signatures.
	•	Canada follows the NIST FIPS 180-4 (SHA-2) and FIPS 202 (SHA-3) standards directly.

There is no indication of a Canadian-only replacement hash. Instead, Canada relies on NIST-standardized SHA-2 and SHA-3, just like the U.S.

---

# NEW ZEALAND
New Zealand’s **cryptographic guidance** is primarily in the NZISM (New Zealand Information Security Manual).

A publicly visible FAQ entry on “Cryptography and associated cryptographic protocols” says:
* GCSB had previously encouraged the use of SHA-384, and as of December 2018, the use of SHA-384 has become a control in the NZISM.
* It refers you to Chapter 17 “Cryptography” and Section 17.2 “Approved cryptographic algorithms” for the full algorithm list.

Key takeaways from that FAQ:
1.	New Zealand’s minimum requirement for hashing algorithms in NZISM-controlled contexts is SHA-384 (which is part of the SHA-2 family).
2.	The detailed list of “approved cryptographic algorithms” is in NZISM Chapter 17, Section 17.2, which is referenced explicitly but the full content is not open on the public FAQ page.

What we can safely conclude:
* New Zealand explicitly bases its hashing requirements on SHA-2, with SHA-384 as a minimum standard for many government use cases.
* It is clear they are following mainstream, internationally accepted primitives (i.e., SHA-2).
* The public FAQ does not explicitly state “SHA-3 is approved/not approved,” but it shows they are anchored on standard NIST-style hashes, not a homegrown New Zealand hash.

So for New Zealand, you can think of it this way:
* SHA-384 (and, by extension, SHA-2) is the baseline requirement.
* Full details of all approved hash functions are in NZISM Section 17.2, but those are not spelled out in the FAQ snippet.
* Like other Five Eyes members, NZ aligns with widely accepted international crypto; there is no “NZ-only” hash function.

## Key New Zealand Cybersecurity Standards & Publications 
(NCSC / GCSB / NZISM / PSR)

This awxrion  lists the major cybersecurity frameworks, policies, controls, and assurance resources from the **National Cyber Security Centre (NCSC New Zealand)**,
the **Government Communications Security Bureau (GCSB)**, and the **Protective Security Requirements (PSR)** framework.


### 🇳🇿 Main Resource Libraries

* NCSC New Zealand – Publications Library - https://www.ncsc.govt.nz/guidance/

### **Government Communications Security Bureau (GCSB)**
- https://www.gcsb.govt.nz/

### **Protective Security Requirements (PSR) Framework**
- https://www.protectivesecurity.govt.nz/

---

## 🧩 Governance, Policy & Assurance

### **Protective Security Requirements (PSR)**
New Zealand’s primary whole-of-government security framework.
- https://www.protectivesecurity.govt.nz/

### **Information Security Management Protocol (ISMP)**
- https://www.protectivesecurity.govt.nz/implementing-the-psr/information-security/

### **New Zealand Information Security Manual (NZISM)**
Equivalent to NIST 800-53 + ISM (Australia) for government systems.
- https://www.gcsb.govt.nz/our-work/information-assurance-and-cyber-security/new-zealand-information-security-manual/

### **PSR Governance & Risk Management**
- https://www.protectivesecurity.govt.nz/governance/

## 🔒 Cryptography (GCSB / NCSC)

### **GCSB Cryptographic Guidance**
- https://www.gcsb.govt.nz/our-work/information-assurance-and-cyber-security/guidance/

### **GCSB Approved Cryptographic Algorithms & Protocols**
- https://www.gcsb.govt.nz/our-work/information-assurance-and-cyber-security/certified-crypto/

### **Quantum-Safe / PQC (NZ Strategic Guidance)**
*NZ follows UK/NIST PQC strategy; high-level guidance provided by NCSC NZ.*
- https://www.ncsc.govt.nz/guidance/

## ☁️ Cloud Security & Assurance

### **NCSC Cloud Security Guidance**
- https://www.ncsc.govt.nz/guidance/cloud-security/

### **NZISM Cloud-Specific Controls**
- https://www.gcsb.govt.nz/our-work/information-assurance-and-cyber-security/new-zealand-information-security-manual/


## 🔄 Incident Response & Threat Management

### **NCSC Cyber Threat Response Guidance**
- https://www.ncsc.govt.nz/incident-response/

### **New Zealand Computer Emergency Response Team (CERT NZ)**
- https://www.cert.govt.nz/

### **CERT NZ Critical Controls**
- https://www.cert.govt.nz/business/guides/critical-controls/

## 🧬 Critical Infrastructure Protection

### **New Zealand CNI Security Guidance (NCSC)**
- https://www.ncsc.govt.nz/critical-national-infrastructure/

### **Sector-Specific Risk Guidance**
- https://www.protectivesecurity.govt.nz/resources-and-guidance/

## 🛡️ Supply Chain Security

### **NCSC Supply Chain Risk Management**
- https://www.ncsc.govt.nz/guidance/supply-chain-risk-management/

### **PSR Supply Chain Security Requirements**
- https://www.protectivesecurity.govt.nz/information-security/

## 👤 Identity, Authentication & Access Control

### **NCSC Identity & Access Management**
- https://www.ncsc.govt.nz/guidance/identity-and-access-management/

### **Government Standards for Authentication**
- https://www.digital.govt.nz/standards-and-guidance/identity/


## 🔧 Secure Development & Architecture

### **NCSC Secure Systems Design Guidance**
- https://www.ncsc.govt.nz/guidance/system-design/

### **NCSC Security Architecture Guidance**
- https://www.ncsc.govt.nz/guidance/architecture/

### **NCSC Secure Development Practices**
- https://www.ncsc.govt.nz/guidance/secure-development/


## 📌 Notes
New Zealand’s security ecosystem revolves around:

- **PSR** → Whole-of-government security framework  
- **NZISM** → The technical controls standard (closest to NIST SP 800-53/ISM AU)  
- **NCSC NZ** → Practical defensive guidance, architecture, IR  
- **GCSB** → Classified cryptographic policy, certification, national security systems  

These four components collectively parallel the role played by NIST, NSA/NCSC

---

# AUSTRALIA

Australia’s primary technical cryptography guidance comes from the Australian Cyber Security Centre (ACSC) via the Information Security Manual (ISM).

A specific ISM cryptography guideline document (December 2024 version) states:
	•	“The only approved hashing algorithm for general purpose use is Secure Hashing Algorithm 2 (SHA-2).”
	•	“However, Secure Hashing Algorithm 3 (SHA-3), including its extendable-output functions (XOFs), is approved exclusively for use within ML-DSA and ML-KEM.”

This tells you:
	1.	For most purposes in Australian government systems following the ISM, SHA-2 is the only general-purpose hashing algorithm you are allowed to use.
	2.	SHA-3 is not banned, but its use is restricted to specific post-quantum constructs (ML-DSA and ML-KEM) as defined in that guidance.

Additionally, a Queensland Government “Data encryption standard” page, which in turn references the ACSC ISM, presents a table of “ASD approved cryptographic algorithms.” In that table:
	•	For “Hash,” it lists “Secure Hashing Algorithm 2 (SHA-2)” with key sizes SHA-224, SHA-256, preferably SHA-384 or SHA-512.

This reinforces that:
	•	SHA-2 is the standard hash family for Australian public-sector cryptography following ACSC/ASD guidance.
	•	SHA-3 is allowed in a limited, controlled context (inside specific PQC algorithms), not as a general-purpose hash.

⸻

# COMPARISON SUMMARY: CANADA, NEW ZEALAND, AUSTRALIA

Canada:
	•	Explicitly recommends SHA-2 and SHA-3 as secure hash algorithms for UNCLASSIFIED, PROTECTED A, and PROTECTED B information, with SHA-1 being phased out.
	•	Relies on NIST’s FIPS 180-4 (SHA-2) and FIPS 202 (SHA-3) for definitions, and lists those by name in ITSP.40.111.

New Zealand:
	•	Uses NZISM as its core manual.
	•	Public FAQ indicates that SHA-384 is the minimum required hash algorithm and that this requirement is codified as a control in NZISM.
	•	Full approved algorithm list is in NZISM Chapter 17, Section 17.2, but the FAQ already shows they are using SHA-2 family hashes as baseline.

Australia:
	•	ISM (cryptography guidelines) says SHA-2 is the only approved general-purpose hashing algorithm.
	•	SHA-3 (and its XOFs) is approved only inside specific post-quantum schemes (ML-DSA and ML-KEM).
	•	A Queensland Government standard, referencing ACSC ISM, gives SHA-2 (with preference for larger output sizes like SHA-384 and SHA-512) as the approved hash in its “ASD approved cryptographic algorithms” table.

⸻

## BIG PICTURE (ALL THREE)
1.	None of these countries has its own “national” hash algorithm; they all rely on standard, well-known primitives (SHA-2 and, in Canada’s case, SHA-3 as well).
2.	There is no export-style restriction on these algorithms themselves. They are openly standardized and meant for global use.
3.	Canada is the clearest in publicly endorsing both SHA-2 and SHA-3. New Zealand explicitly uses SHA-384 (SHA-2). Australia officially allows SHA-2 generally and SHA-3 in specialized PQC contexts.




### **UK Government Security**


# Key Canadian Cybersecurity Standards & Publications (CCCS / CSE / TBS)

This document lists the main cybersecurity frameworks, policies, and technical
guidance issued by the **Canadian Centre for Cyber Security (CCCS)**,
**Communications Security Establishment (CSE)**, and **Treasury Board Secretariat (TBS)**.

---

## 🇨🇦 Main Resource Libraries

### **Canadian Centre for Cyber Security (CCCS) – Publications**
- https://www.cyber.gc.ca/en/guidance

### **Government of Canada Security Policy Suite**
- https://www.canada.ca/en/treasury-board-secretariat/services/access-information-privacy/security-policy.html

---

## 🧩 Governance, Policy & Assurance

### **Policy on Government Security (PGS)**
- https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=16578

### **Directive on Security Management**
- https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=27965

### **Government of Canada IT Security Risk Management (ITSG-33)**
*Canada’s closest equivalent to NIST RMF (800-37 + 800-53).*
- https://www.cyber.gc.ca/en/guidance/it-security-risk-management-itsg-33

### **Security Assessment & Authorization (SA&A) Guidance**
- https://www.cyber.gc.ca/en/guidance/itsg-33-ita

---

## 🔒 Cryptography (CSE / CCCS)

### **CSE Top 10 Security & Crypto Publications**
- https://www.cyber.gc.ca/en/guidance/top-10-cse-it-security-publications

### **ITSP.40 – Government of Canada Cryptographic Algorithms**
- https://www.cyber.gc.ca/en/guidance/itsp40-government-canada-cryptographic-algorithms-while-government-canada-systems

### **ITSP.30 – Secure Cryptographic Design**
- https://www.cyber.gc.ca/en/guidance/itsp30-secure-design-and-implementation-cryptographic-solutions

### **Quantum-Safe Cryptography (Canada PQC Roadmap)**
- https://www.cyber.gc.ca/en/guidance/quantum-safe-guidance

---

## 🔄 Incident Response & Cyber Resilience

### **Canadian Cyber Incident Response Centre (CCIRC) Guidance**
- https://www.cyber.gc.ca/en/cyber-incident-management

### **CCCS Assessment & Vulnerability Guidance**
- https://www.cyber.gc.ca/en/guidance/assessments-and-vulnerability-management

---

## ☁️ Cloud Security (GC Cloud)

### **GC Cloud Security Controls**
- https://www.canada.ca/en/government/system/digital-government/modern-emerging-technologies/cloud-security-controls.html

### **Canadian Protected B Cloud Guidance**
- https://www.canada.ca/en/government/system/digital-government/modern-emerging-technologies/cloud-security-risk-management.html

---

## 🧬 Supply Chain & Critical Infrastructure

### **National Strategy for Critical Infrastructure**
- https://www.publicsafety.gc.ca/cnt/rsrcs/pblctns/srtg-crtcl-nfrstrctr/index-en.aspx

### **CCCS Supply Chain Cybersecurity Guidance**
- https://www.cyber.gc.ca/en/collection/supply-chain-security

---

## 👤 Identity, Authentication & Privacy

### **Pan-Canadian Trust Framework (PCTF)**  
(Digital identity interoperability standard)
- https://diacc.ca/trust-framework/

### **TBS Privacy & Identity Policy Instruments**
- https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=32654

---

## 🔧 Secure Development & Architecture

### **CCCS Secure Software Guidance**
- https://www.cyber.gc.ca/en/guidance/software-and-endpoint-security

### **CCCS Architecture / Design Hardening**
- https://www.cyber.gc.ca/en/guidance/network-security

---

## 📌 Notes
Canada’s main security framework is **ITSG-33**, and CCCS materials align closely to NIST SPs and NSA/CSE cooperative standards under the Five Eyes partnership.


# Key Australian Cybersecurity Standards & Publications (ACSC / ASD / PSPF / ISM)

This document lists the major cybersecurity frameworks and publications from the  
**Australian Cyber Security Centre (ACSC)** and **Australian Signals Directorate (ASD)**,  
including the **ISM**, **Essential Eight**, cloud guidance, and critical infrastructure rules.

---

## 🇦🇺 Main Resource Libraries

### **ACSC – Cyber Security Guidance Library**
- https://www.cyber.gov.au/resources-business-and-government

### **Australian Signals Directorate (ASD)**
- https://www.asd.gov.au/

### **Australian Government Information Security Manual (ISM)**
- https://www.cyber.gov.au/resources-business-and-government/government-security/ism

---

## 🧩 Governance, Assurance & Risk

### **Information Security Manual (ISM)**
Australia’s equivalent to NIST 800-53 + 800-37 + CNSSI 1253.
- https://www.cyber.gov.au/resources-business-and-government/government-security/ism

### **Protective Security Policy Framework (PSPF)**
- https://www.protectivesecurity.gov.au/

### **Essential Eight Maturity Model**
- https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/essential-eight

### **Risk Management Guidance**
- https://www.cyber.gov.au/resources-business-and-government/risk-management

---

## 🔒 Cryptography (ASD)

### **Australian Government Cryptographic Policy**
- https://www.cyber.gov.au/resources-business-and-government/government-security/cryptographic-policy

### **Evaluated Product List (EPL) – ASD Approved Crypto & Security Products**
- https://www.asd.gov.au/acsccertifiedproducts

### **Australian PQC Guidance (Quantum-Safe Readiness)**
- https://www.cyber.gov.au/acsc/view-all-content/publications/preparing-quantum-safe-cryptography

---

## ☁️ Cloud Security

### **ACSC Cloud Security Guidance**
- https://www.cyber.gov.au/resources-business-and-government/government-security/cloud-security-guidance

### **Cloud Security Controls & Assessments**
- https://www.cyber.gov.au/resources-business-and-government/government-security/cloud

---

## 🔄 Incident Response & Threat Intelligence

### **ACSC Incident Response**
- https://www.cyber.gov.au/report-and-manage

### **ACSC Partner Programme / Threat Sharing**
- https://www.cyber.gov.au/acsc-partners

---

## 🧬 Critical Infrastructure Protection (SoCI Act)

### **Security of Critical Infrastructure (SoCI) Framework**
- https://www.cisc.gov.au/

### **Critical Infrastructure Cyber Uplift Guidance**
- https://www.cisc.gov.au/guidance

---

## 🛡️ Supply Chain Security

### **ACSC Supply Chain Risk Management Guidance**
- https://www.cyber.gov.au/resources-business-and-government/government-security/supply-chain-security

---

## 👤 Identity, Authentication & Governance

### **Digital Identity – Australian Government Trust Framework (AGTF)**
- https://www.digitalidentity.gov.au/

### **ACSC Identity & Access Management Guidance**
- https://www.cyber.gov.au/resources-business-and-government/authentication

---

## 🔧 Secure Development & Architecture

### **ACSC Secure Coding & Development**
- https://www.cyber.gov.au/resources-business-and-government/developers

### **ACSC Architecture / Patterns / Hardening Guidance**
- https://www.cyber.gov.au/resources-business-and-government/system-hardening

---

## 📌 Notes
Australia’s **ISM** + **PSPF** + **Essential Eight** serve as the core of its cybersecurity framework, and map closely to U.S. NIST controls, U.K. NCSC guidance, and Canada’s ITSG-33 as part of broader Five Eyes collaboration.


# Key New Zealand Cybersecurity Standards & Publications (NCSC / GCSB / NZISM / PSR)

This document lists the major cybersecurity frameworks, policies, controls, and
assurance resources from the **National Cyber Security Centre (NCSC New Zealand)**,
the **Government Communications Security Bureau (GCSB)**, and the **Protective
Security Requirements (PSR)** framework.

---

## 🇳🇿 Main Resource Libraries

### **NCSC New Zealand – Publications Library**
- https://www.ncsc.govt.nz/guidance/

### **Government Communications Security Bureau (GCSB)**
- https://www.gcsb.govt.nz/

### **Protective Security Requirements (PSR) Framework**
- https://www.protectivesecurity.govt.nz/

---

## 🧩 Governance, Policy & Assurance

### **Protective Security Requirements (PSR)**
New Zealand’s primary whole-of-government security framework.
- https://www.protectivesecurity.govt.nz/

### **Information Security Management Protocol (ISMP)**
- https://www.protectivesecurity.govt.nz/implementing-the-psr/information-security/

### **New Zealand Information Security Manual (NZISM)**
Equivalent to NIST 800-53 + ISM (Australia) for government systems.
- https://www.gcsb.govt.nz/our-work/information-assurance-and-cyber-security/new-zealand-information-security-manual/

### **PSR Governance & Risk Management**
- https://www.protectivesecurity.govt.nz/governance/

---

## 🔒 Cryptography (GCSB / NCSC)

### **GCSB Cryptographic Guidance**
- https://www.gcsb.govt.nz/our-work/information-assurance-and-cyber-security/guidance/

### **GCSB Approved Cryptographic Algorithms & Protocols**
- https://www.gcsb.govt.nz/our-work/information-assurance-and-cyber-security/certified-crypto/

### **Quantum-Safe / PQC (NZ Strategic Guidance)**
*NZ follows UK/NIST PQC strategy; high-level guidance provided by NCSC NZ.*
- https://www.ncsc.govt.nz/guidance/

---

## ☁️ Cloud Security & Assurance

### **NCSC Cloud Security Guidance**
- https://www.ncsc.govt.nz/guidance/cloud-security/

### **NZISM Cloud-Specific Controls**
- https://www.gcsb.govt.nz/our-work/information-assurance-and-cyber-security/new-zealand-information-security-manual/

---

## 🔄 Incident Response & Threat Management

### **NCSC Cyber Threat Response Guidance**
- https://www.ncsc.govt.nz/incident-response/

### **New Zealand Computer Emergency Response Team (CERT NZ)**
- https://www.cert.govt.nz/

### **CERT NZ Critical Controls**
- https://www.cert.govt.nz/business/guides/critical-controls/

---

## 🧬 Critical Infrastructure Protection

### **New Zealand CNI Security Guidance (NCSC)**
- https://www.ncsc.govt.nz/critical-national-infrastructure/

### **Sector-Specific Risk Guidance**
- https://www.protectivesecurity.govt.nz/resources-and-guidance/

---

## 🛡️ Supply Chain Security

### **NCSC Supply Chain Risk Management**
- https://www.ncsc.govt.nz/guidance/supply-chain-risk-management/

### **PSR Supply Chain Security Requirements**
- https://www.protectivesecurity.govt.nz/information-security/

---

## 👤 Identity, Authentication & Access Control

### **NCSC Identity & Access Management**
- https://www.ncsc.govt.nz/guidance/identity-and-access-management/

### **Government Standards for Authentication**
- https://www.digital.govt.nz/standards-and-guidance/identity/

---

## 🔧 Secure Development & Architecture

### **NCSC Secure Systems Design Guidance**
- https://www.ncsc.govt.nz/guidance/system-design/

### **NCSC Security Architecture Guidance**
- https://www.ncsc.govt.nz/guidance/architecture/

### **NCSC Secure Development Practices**
- https://www.ncsc.govt.nz/guidance/secure-development/

---

## 📌 Notes
New Zealand’s security ecosystem revolves around:

- **PSR** → Whole-of-government security framework  
- **NZISM** → The technical controls standard (closest to NIST SP 800-53/ISM AU)  
- **NCSC NZ** → Practical defensive guidance, architecture, IR  
- **GCSB** → Classified cryptographic policy, certification, national security systems  

These four components collectively parallel the role played by NIST, NSA/NCSC
