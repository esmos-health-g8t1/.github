# 🏥 ESMOS Healthcare G8T1

High-assurance, cloud-native digital ecosystems tailored for modern healthcare providers. Focused on regulatory compliance, operational efficiency, and clinical staff readiness via a unified, secure platform.

---

## 🎯 Strategic Objective

Achieve a "Blueprint for Value" in healthcare IT by integrating operational excellence with mandatory compliance. Operations follow the **ITIL 4.0 DevSecOps** framework to ensure every service transition creates measurable stakeholder value while maintaining a zero-trust security posture.

---

## 🧩 Platform Ecosystem

The ESMOS platform consolidates essential healthcare services into a unified, serverless environment:

| Service | Category | Key Capability |
| :--- | :--- | :--- |
| **ESMOS Operations** (Odoo) | ERP & Supply Chain | Real-time medical stock and meal plan tracking. |
| **ESMOS Academy** (Moodle) | Training & Compliance | Mandatory certification gates for system access. |
| **ESMOS Support** (Peppermint) | ITIL Service Desk | Single Point of Contact (SPOC) for clinical staff. |

---

## 🛡️ Engineering Standards

All infrastructure and application code within the ESMOS organization adheres to a rigorous "Security & Compliance Baseline":

### 1. Cloud-Native & Serverless Architecture
Priority is given to **Azure Container Apps (ACA)** to eliminate host-level maintenance debt. Elastic scalability (KEDA) ensures system stability during concurrent staff training spikes or emergency inventory updates.

### 2. Zero-Trust Security & Identity
*   **OIDC Federation**: Deployment pipelines utilize Workload Identity Federation (GitHub Actions OIDC) to eliminate static credentials.
*   **Secret Management**: Mandatory integration with **Azure Key Vault** with a zero-manual-secret policy.
*   **VNet Isolation**: Multi-tier network air-gapping isolates frontend edge services from backend data layers.

### 3. Data Residency & Sovereignty
Strict **Asia-Pacific (Southeast Asia)** data residency is enforced via automated Azure Policies. All medical records and PII remain within compliant jurisdictional boundaries.

---

## 🔧 DevSecOps Toolchain

Infrastructure is managed as versioned product code:
*   **IaC**: [Terraform](https://www.terraform.io/) for 100% reproducible environments.
*   **CI/CD**: GitHub Actions with integrated **Trivy** vulnerability scanning.
*   **Observability**: Centralized Log Analytics with **Azure Managed Grafana** for high-fidelity diagnostics.

---

## 📈 ITIL 4.0 Governance

Operations are managed through the **Service Value System (SVS)**:
*   **Plan**: Business-aligned service strategy.
*   **Design & Transition**: Risk-managed deployments with automated recovery.
*   **Deliver & Support**: SLA-backed operations via the integrated ticketing portal.
*   **Improve**: Telemetry-driven lifecycle management and continuous feedback.

---

## 📫 Access & Support

Clinical staff requiring assistance or developers contributing to the ESMOS core should utilize the **Peppermint Service Portal** or the designated `#incidents` emergency channel.

---
*© IS214 Enterprise Solution Management - G8T1*