# CIP-B106 Mobile and IoT Forensics  
## iOS 13.4.1 Case Study

**Student:** Mary Ekwughaonu  
**Registration Number:** c11.dfit2617295  
**Case Identifier:** CIPB106-iOS13-c11.dfit2617295  
**Submission Date:** 4 October 2026  

---

### Case Overview
Forensic examination of a supplied iPhone iOS 13.4.1 file-system extraction.  
The examination reconstructed device/account profile, communications, organiser artefacts, KnowledgeC activity and selected user activity around 11–12 April 2020.

### Key Findings
- Device running **iOS 13.4.1 (Build 17E262)**
- SMS/iMessage verification codes recovered
- Calendar event “Pick up lunch” identified
- KnowledgeC records show use of Facebook Messenger, CyberDust and native Photos
- No observable jailbreak indicators located

### Evidence Integrity
| File                    | MD5                              | SHA-256                                                         |
|-------------------------|----------------------------------|-----------------------------------------------------------------|
| ios_13_4_1.zip          | 4e094801ba1e3b938b2c0cc18d0e0d1d | 761854a669c38da6ac0a908afe77763d54ccb83044ff123350890d408c154551 |

### Repository Contents
- `CIP-B106_CaseStudy_c11.dfit2617295_Mary_Ekwughaonu.pdf` – Full case study report
- `Hashes/` – MD5 and SHA-256 of original evidence
- `Working/reports/` – Extracted SQLite queries, KnowledgeC activity, messages, calendar findings

### Tools Used
- Kali Linux
- sqlite3, plutil, find, grep, Python 3 (Cocoa timestamp conversion)

### Academic Integrity
This work was performed on the authorised course evidence only.  
All conclusions are limited to what the recovered artefacts can support.

### Disclaimer
Training material only. Not related to any real investigation.
