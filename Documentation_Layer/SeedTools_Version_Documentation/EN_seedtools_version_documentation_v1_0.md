# **🔥 1. When does documentation MUST be versioned?**

If the document:

- defines a standard,
- describes a framework,
- is part of a security architecture,
- is part of the RX‑Series or FA‑Series,
- is part of ransomware modules,
- is part of the Enterprise Architecture,
- is part of Governance, Compliance, Recovery, Defense, Security, Audit.

→ **must be versioned**.

### Examples:

- **EN_seedtools_ransomware_compliance_standard_v1_0.md**
- **EN_seedtools_ransomware_recovery_framework_v1_0.md**
- **EN_seedtools_enterprise_security_charter_v1_0.md**
- **EN_seedtools_post_incident_governance_framework_v1_0.md**
- **EN_seedtools_ransomware_defense_matrix_v1_0.md**
- **EN_seedtools_ransomware_severity_index_v1_0.md**
- **EN_seedtools_encryption_timeline_v1_0.md**
- **EN_seedtools_forensic_workflow_v1_0.md**

These are **formal standards** documents, so a version is mandatory.

--

# **🔥 2. When does documentation NOT need to be versioned?**

If the document:

- is an instruction,
- is a guide,
- is an operational workflow,
- is a supporting document,
- is an index,
- is a repo or folder standard,
- is onboarding,
- is Rustup documentation,
- is an example,
- is a PDF,

→ **does not need to be versioned**.

### Examples:

- **EN_seedtools_documentation_workflow.md**
- **EN_seedtools_documentation_index.md**
- **EN_seedtools_folder_naming_standard.md**
- **EN_seedtools_repo_standard.md**
- **EN_seedtools_onboarding_guide.md**
- **EN_rustup_backup_workflow_deterministic_safe.md**
- **EN_rustup_restore_workflow_deterministic_safe.md**
- **SeedTools_Rustup_Migration_Guide.pdf**
- **deterministic_test_output.txt**

These are **operational** documents, not formal - no revision required.

---

# **🔥 3. SeedTools Enterprise Rule (most important)**

### **If a document affects security → it has a version.**
### **If a document affects workflow → a version is not required.**

This is the foundation of the entire architecture.

---
