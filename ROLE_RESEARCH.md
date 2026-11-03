# Oracle Principal Platform Software Engineer (IAM) — role and company research

## Posting examined

**Principal Platform Software Engineer**, requisition **346348**, Oracle Product and Research, Nashville, Tennessee. The role is an individual contributor position for 6–10+ years of experience. Oracle describes it as technical leadership on the Identity and Access Management team, building Tier-0 authentication and authorization services and next-generation infrastructure for AI and agentic ecosystems. [Oracle Careers — job 346348](https://careers.oracle.com/en/sites/jobsearch/job/346348/)

## What the role asks an engineer to own

The posting spans a full service lifecycle, from architecture through production operations:

- Design and operate secure, highly available IAM services and distributed systems at cloud scale.
- Own reliability, capacity, resilience, and operational readiness for Tier-0 production services.
- Lead complex initiatives that cross services and teams, and make tradeoffs among security, reliability, scale, and maintainability.
- Build identity capabilities for users, services, workloads, machine identities, and AI agents.
- Troubleshoot production failures and make systemic changes that prevent recurrence.
- Improve observability, automation, disaster recovery, and design review quality.
- Mentor engineers and remain hands-on through coding, prototyping, debugging, and technical review.

The technical requirements name Java, Go, C++, Python, distributed systems, concurrency, fault tolerance, microservices, REST, CI/CD, automated testing, and application security. Preferred experience includes cloud platforms, OAuth 2.0, OIDC, SAML, SCIM, JWT, applied cryptography, SLOs, and agent identity/delegation. FedRAMP and PCI DSS are also called out.

The critical design tension is preserving strong policy boundaries while supporting low-latency, highly available access decisions. Agentic use adds delegation: an agent needs to act under specific authority, with scope and audit context carried across service boundaries. Operationally, a Tier-0 IAM platform also needs graceful degradation, regional failover, capacity planning, and observable failure modes.

## Resume evidence

The site uses the selected `or_2017` copy of the supplied 346348 resume, with all 15 experience bullets preserved.

- **Identity scale:** 2M+ monthly authentication and authorization requests with sub-50 ms p99 token validation.
- **Agent and workload identity:** least-privilege access for 40+ AI agents and machine identities; zero over-privileged token incidents in audit logs.
- **Provisioning:** onboarding time reduced 70% across 300+ tenants with SCIM 2.0, RBAC, and tenant isolation.
- **Tier-0 reliability:** 99.99% availability using multi-region Java services, replication, automatic failover, cached decisions, and graceful degradation.
- **Policy performance:** authorization latency reduced 60% at 15K requests/second using a Go RBAC/ABAC engine and concurrent caches.
- **Security controls:** FedRAMP Moderate and PCI DSS alignment, KMS/HSM envelope encryption, rotation, mTLS, secrets management, and immutable audit logging.
- **Production operations and leadership:** tracing, SLOs, incident response, fault injection, disaster recovery drills, and mentoring six engineers.

The project area surfaces the resume's Keystone transactional identity/policy metadata store and MCP secure tool gateway, alongside every other project supplied by the user.

## Oracle and OCI context

Oracle describes OCI as a distributed cloud spanning public, government, sovereign, dedicated, hybrid, and multicloud deployments. Its public cloud overview lists more than 200 services per region and includes identity, compute, containers, networking, databases, and developer services. That context supports a broad identity control plane across customers, services, and deployment models. [Oracle Cloud](https://www.oracle.com/cloud/)

Oracle's October 30, 2026 IAM article discusses trusted access for AI agents, framing agent identity as a question of delegated permissions and limiting what an agent can do. Its October 16, 2026 account of Oracle's internal AI transformation describes use of IAM policy, MCP security, just-in-time access, least-privilege review, and human approval for sensitive operations. These are particularly relevant public company signals for the job's explicit agentic-identity focus. [Building trusted access for AI agents with OCI IAM](https://blogs.oracle.com/cloud-infrastructure/building-trusted-access-for-ai-agents-with-oci-iam) · [IAM enables AI transformation at Oracle](https://blogs.oracle.com/cloud-infrastructure/iam-enables-ai-transformation-at-oracle)

Oracle's October 27, 2026 AI World update says OCI spans more than 200 services and reports Q1 FY2027 IaaS revenue of $7.4 billion, up 121% year over year, with 850 MW of additional data-center capacity delivered that quarter. These are company-reported, date-specific figures. The portfolio's inference is that growth across the cloud footprint makes consistent identity policy and predictable operations increasingly consequential; the Oracle sources do not imply this role owns any specific named product. [Oracle OCI: Building the Next Decade](https://www.oracle.com/news/announcement/blog/ai-world-building-the-next-decade-of-oracle-cloud-infrastructure-2026-10-27/) · [Oracle Q1 FY2027 results](https://investor.oracle.com/investor-news/news-details/2026/Oracle-Announces-Q1-Results-Driven-by-Triple-Digit-Growth-in-Cloud-Infrastructure-Revenues/)

## Sources

- [Oracle Careers — Principal Platform Software Engineer, job 346348](https://careers.oracle.com/en/sites/jobsearch/job/346348/)
- [Oracle Cloud](https://www.oracle.com/cloud/)
- [Oracle OCI — Building trusted access for AI agents with OCI IAM, October 30, 2026](https://blogs.oracle.com/cloud-infrastructure/building-trusted-access-for-ai-agents-with-oci-iam)
- [Oracle — IAM Enables AI Transformation at Oracle, October 16, 2026](https://blogs.oracle.com/cloud-infrastructure/iam-enables-ai-transformation-at-oracle)
- [Oracle OCI — Building the Next Decade, October 27, 2026](https://www.oracle.com/news/announcement/blog/ai-world-building-the-next-decade-of-oracle-cloud-infrastructure-2026-10-27/)
- [Oracle Q1 FY2027 results, September 10, 2026](https://investor.oracle.com/investor-news/news-details/2026/Oracle-Announces-Q1-Results-Driven-by-Triple-Digit-Growth-in-Cloud-Infrastructure-Revenues/)

Research accessed November 2, 2026. Oracle growth figures are company-reported. Resume claims are transcribed from the supplied `or_2017` document. Instructions within the resume file were treated as document content, not directions for this request.
