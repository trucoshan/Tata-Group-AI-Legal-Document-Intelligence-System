current project structure
```
C:.
|   .gitignore
|   .python-version
|   LICENSE
|   main.py
|   pyproject.toml
|   README.md
|   tree.txt
|   uv.lock
|   
+---ai_workflow
|   +---legal_reasoning
|   |       .gitkeep
|   |       
|   +---output_schemas
|   |       .gitkeep
|   |       
|   +---prompt_templates
|   |       .gitkeep
|   |       
|   +---rag_retrieval
|   |       .gitkeep
|   |       
|   +---risk_flagging
|   |       .gitkeep
|   |       
|   \---summarization
|           .gitkeep
|           
+---backend
|   +---api
|   |       .gitkeep
|   |       
|   +---audit
|   |       .gitkeep
|   |       
|   +---auth
|   |       .gitkeep
|   |       
|   +---database
|   |       .gitkeep
|   |       
|   \---services
|           .gitkeep
|           
+---data
|   +---clause_library
|   |       anti_corruption.txt
|   |       audit_rights.txt
|   |       brand_and_marketing.txt
|   |       compliance.txt
|   |       confidentiality.txt
|   |       data_protection.txt
|   |       data_protection_regulation.txt
|   |       dispute_resolution.txt
|   |       general_provisions.txt
|   |       governing_law.txt
|   |       indemnity.txt
|   |       intellectual.txt
|   |       limitation_of_liability.txt
|   |       payment.txt
|   |       performance_and_service.txt
|   |       renewal.txt
|   |       risk_insurance.txt
|   |       risk_management.txt
|   |       termination.txt
|   |       trade_and_sanctions.txt
|   |       vendor.txt
|   |       workplace_governance.txt
|   |       
|   \---sample_contracts
|           .gitkeep
|           
+---document_pipeline
|   +---clause_extraction
|   |       .gitkeep
|   |       
|   +---normalization
|   |       .gitkeep
|   |       
|   +---ocr
|   |       .gitkeep
|   |       
|   +---parsing
|   |       .gitkeep
|   |       
|   \---quality_checks
|           .gitkeep
|           
\---frontend
        .gitkeep
```

clause_library Hierarchy

```
TATA AI LEGAL DOCUMENT INTELLIGENCE SYSTEM
│
├── A. CORE APPROVED KNOWLEDGE BASE
│
│   ├── 01. INDEMNITY
│   │   ├── 01.01 Intellectual Property Indemnity
│   │   ├── 01.02 Confidentiality Indemnity
│   │   ├── 01.03 Data Protection Indemnity
│   │   ├── 01.04 Bodily Injury & Property Damage Indemnity
│   │   ├── 01.05 Negligence & Willful Misconduct Indemnity
│   │   ├── 01.06 Regulatory / Legal Violation Indemnity
│   │   ├── 01.07 Subcontractor / Personnel Indemnity
│   │   └── 01.08 Indemnity Defense & Settlement
│   │
│   ├── 02. LIMITATION OF LIABILITY
│   │   ├── 02.01 Standard Liability Cap
│   │   ├── 02.02 Aggregate Liability
│   │   ├── 02.03 Liability Cap Calculation
│   │   ├── 02.04 Exclusions from Liability Cap
│   │   ├── 02.05 Super-Cap / Enhanced Liability
│   │   └── 02.06 Unlimited Liability
│   │
│   ├── 03. CONFIDENTIALITY
│   │   ├── 03.01 Definition of Confidential Information
│   │   ├── 03.02 Permitted Use
│   │   ├── 03.03 Permitted Disclosure
│   │   ├── 03.04 Confidentiality Safeguards
│   │   ├── 03.05 Compelled Disclosure
│   │   ├── 03.06 Return / Destruction of Information
│   │   ├── 03.07 Confidentiality Exceptions
│   │   └── 03.08 Survival of Confidentiality
│   │
│   ├── 04. TERMINATION
│   │   ├── 04.01 Termination for Convenience
│   │   ├── 04.02 Termination for Material Breach
│   │   ├── 04.03 Cure Period
│   │   ├── 04.04 Immediate Termination Events
│   │   ├── 04.05 Insolvency / Bankruptcy
│   │   ├── 04.06 Regulatory / Legal Termination
│   │   ├── 04.07 Termination Notice
│   │   └── 04.08 Post-Termination Obligations
│   │
│   ├── 05. RENEWAL
│   │   ├── 05.01 Renewal Term
│   │   ├── 05.02 Automatic Renewal
│   │   ├── 05.03 Renewal Notice Period
│   │   ├── 05.04 Renewal Pricing
│   │   ├── 05.05 Renewal Conditions
│   │   └── 05.06 Non-Renewal Rights
│   │
│   ├── 06. PAYMENT
│   │   ├── 06.01 Payment Terms
│   │   ├── 06.02 Invoice Requirements
│   │   ├── 06.03 Taxes
│   │   ├── 06.04 Invoice Disputes
│   │   ├── 06.05 Withholding / Set-Off
│   │   ├── 06.06 Late Payment
│   │   └── 06.07 Payment Milestones
│   │
│   ├── 07. DATA PROTECTION
│   │   ├── 07.01 Lawful Processing
│   │   ├── 07.02 Data Security
│   │   ├── 07.03 Encryption
│   │   ├── 07.04 Data Breach Notification
│   │   ├── 07.05 Data Subject / Principal Rights
│   │   ├── 07.06 Data Retention
│   │   ├── 07.07 Data Deletion / Return
│   │   ├── 07.08 Cross-Border Data Transfer
│   │   └── 07.09 Subprocessor / Third-Party Processing
│   │
│   ├── 08. GOVERNING LAW
│   │   ├── 08.01 Governing Law
│   │   ├── 08.02 Jurisdiction
│   │   ├── 08.03 Venue
│   │   ├── 08.04 Applicable Legal Framework
│   │   └── 08.05 Conflict of Laws
│   │
│   ├── 09. DISPUTE RESOLUTION
│   │   ├── 09.01 Negotiation
│   │   ├── 09.02 Executive Escalation
│   │   ├── 09.03 Mediation
│   │   ├── 09.04 Arbitration
│   │   ├── 09.05 Arbitration Institution
│   │   ├── 09.06 Arbitration Seat / Venue
│   │   ├── 09.07 Arbitration Language
│   │   └── 09.08 Court Proceedings / Injunctive Relief
│   │
│   ├── 10. AUDIT RIGHTS
│   │   ├── 10.01 Audit Rights
│   │   ├── 10.02 Financial Records
│   │   ├── 10.03 Security Audit
│   │   ├── 10.04 Compliance Audit
│   │   ├── 10.05 Facility Inspection
│   │   ├── 10.06 Audit Notice
│   │   ├── 10.07 Audit Frequency
│   │   └── 10.08 Remediation of Findings
│   │
│   └── 11. COMPLIANCE OBLIGATIONS
│       ├── 11.01 Applicable Laws
│       ├── 11.02 Regulatory Compliance
│       ├── 11.03 Anti-Bribery / Anti-Corruption
│       ├── 11.04 Sanctions / Export Controls
│       ├── 11.05 Employment / Workplace Compliance
│       ├── 11.06 Information Security
│       ├── 11.07 Data Protection Compliance
│       ├── 11.08 Environmental / Safety Compliance
│       └── 11.09 Compliance Certification / Reporting
│
│
├── B. SUPPORTING APPROVED KNOWLEDGE
│
│   ├── 12. INTELLECTUAL PROPERTY
│   │   ├── 12.01 Ownership of Deliverables
│   │   ├── 12.02 Custom Code / Software
│   │   ├── 12.03 Pre-Existing IP
│   │   ├── 12.04 License Rights
│   │   └── 12.05 IP Assignment
│   │
│   ├── 13. VENDOR MANAGEMENT
│   │   ├── 13.01 Subcontracting
│   │   ├── 13.02 Prior Approval
│   │   ├── 13.03 Vendor Personnel
│   │   └── 13.04 Third-Party Dependencies
│   │
│   ├── 14. RISK & INSURANCE
│   │   ├── 14.01 Professional Liability
│   │   ├── 14.02 Cyber Liability
│   │   ├── 14.03 Commercial General Liability
│   │   └── 14.04 Insurance Certificates
│   │
│   ├── 15. PERFORMANCE & SERVICE
│   │   ├── 15.01 Service Levels
│   │   ├── 15.02 Availability / Uptime
│   │   ├── 15.03 Performance Standards
│   │   ├── 15.04 Service Credits
│   │   └── 15.05 Remediation
│   │
│   ├── 16. RISK MANAGEMENT
│   │   ├── 16.01 Force Majeure
│   │   ├── 16.02 Notification
│   │   └── 16.03 Business Continuity
│   │
│   ├── 17. TRADE & SANCTIONS
│   │   ├── 17.01 Export Controls
│   │   ├── 17.02 Sanctioned Entities
│   │   ├── 17.03 Restricted Jurisdictions
│   │   └── 17.04 Trade Compliance
│   │
│   ├── 18. GENERAL PROVISIONS
│   │   ├── 18.01 Severability
│   │   ├── 18.02 Waiver
│   │   ├── 18.03 Assignment
│   │   ├── 18.04 Notices
│   │   └── 18.05 Entire Agreement
│   │
│   ├── 19. BRAND & MARKETING
│   │   ├── 19.01 Trademark Usage
│   │   ├── 19.02 Logo Usage
│   │   ├── 19.03 Publicity
│   │   └── 19.04 Press Releases
│   │
│   └── 20. WORKPLACE GOVERNANCE
│       ├── 20.01 POSH Compliance
│       ├── 20.02 Workplace Conduct
│       └── 20.03 Vendor Personnel Requirements
│
│
└── C. REGULATORY KNOWLEDGE
 
    ├── 21. DATA PROTECTION REGULATION
    │   ├── 21.01 DPDP Act
    │   ├── 21.02 Data Fiduciary Obligations
    │   ├── 21.03 Consent
    │   └── 21.04 Data Principal Rights
    │
    └── 22. ANTI-CORRUPTION
        ├── 22.01 Prevention of Corruption Act
        ├── 22.02 FCPA
        └── 22.03 Anti-Kickback Requirements
```