# Proposed README Additions

## Terminologies

**MSP (Managed Service Provider):** A company that remotely manages a
customer's IT infrastructure and end‑user systems on a proactive basis,
typically under a subscription model.

**MSSP (Managed Security Service Provider):** A specialized MSP that
focuses specifically on providing security monitoring, threat detection,
incident response, and compliance services.

**CMDB (Configuration Management Database):** A centralized repository
that stores information about IT assets (configuration items) and their
relationships. It is a core component of IT service management.

**EDIA:** Typically refers to data ingestion or integration pipelines
that collect and normalize data from external discovery or inventory
sources. (Confirm internal meaning if EDIA has a product‑specific
definition.)

**Shadow IT:** Hardware or software used within an organization without
explicit approval from the IT or security team, creating visibility and
security risks.

**CPEs (Common Platform Enumerations):** A standardized naming scheme
for IT systems, software, and hardware used to identify affected
products in vulnerability databases.

**SLA (Service Level Agreement):** A formal contract that defines
expected service performance (uptime, response time, resolution time)
between a service provider and customer.

**Vulnerability Types in Companies:** - Misconfigurations - Outdated
software / missing patches - Weak authentication - Exposed services -
Zero‑day vulnerabilities - Compliance violations

**EDR (Endpoint Detection and Response):** Security technology that
continuously monitors endpoints (laptops, servers, etc.) to detect,
investigate, and respond to threats.

**Missles (Likely "Misconfigurations" --- confirm):** Security
weaknesses caused by improper system or application configuration.

**ITSM (IT Service Management):** The set of processes and tools used to
design, deliver, manage, and improve IT services within an organization.

**IAM (Identity and Access Management):** Framework of policies and
technologies that ensures the right individuals have appropriate access
to technology resources.

**HDAR (Host Detection and Response --- confirm term):** Security
capability focused on monitoring and responding to threats at the host
level.

**Vulnerability Scanners (Common Types):** - Network‑based scanners -
Host‑based scanners - Web application scanners - Cloud security
scanners - Container security scanners

**Tenant:** A logically isolated customer environment within a
multi‑tenant platform.

**MTTTR (Mean Time To Remediate/Repair):** Average time taken to fix or
remediate identified vulnerabilities or incidents.

------------------------------------------------------------------------

## Key Features

1.  **Normalize First Seen and Last Seen**\
    Standardizes asset observation timestamps across multiple data
    sources to improve asset lifecycle accuracy.

2.  **Mean Time to Repair Metrics for Vulnerabilities**\
    Calculates the average time taken to remediate vulnerabilities,
    helping track security posture and team efficiency.

3.  **Role‑Based Device Access Restriction**\
    Enforces RBAC policies to ensure only authorized roles can view or
    manage specific devices.

4.  **Vulnerability SA (Situational Awareness)**\
    Provides consolidated visibility into vulnerability posture across
    assets, environments, and tenants.

5.  **Non‑CVE Vulnerabilities Integration**\
    Supports ingestion and tracking of security issues that do not have
    CVE identifiers (e.g., vendor advisories, misconfigurations, policy
    violations).
