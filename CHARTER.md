# Launchpad SIG Governance

_Adopted 2.5.26_

ORBIT Launchpad exists to connect the maintainers of open source supply chain security tooling to their end users in a way that facilitates mutually beneficial alignment. 
The ORBIT Launchpad provides support, feedback, and coordination to ORBIT projects without superseding the independence and governance of each.
Documents such as guides, use cases, and best practices are maintained by the community, under the oversight of the SIG Approvers. Everyday operations of the SIG are overseen by a rotating chairperson, appointed by a committee of their peer Approvers.

## Guiding Governing Principles

### Do no harm

In our efforts to improve security within open source, we will not increase the burden on maintainers. We will actively seek to engage with maintainers to reduce the burden of security compliance.

### Open transparency

Evolving regulatory requirements are a challenge for manufacturers as we prepare to meet the CRA in 2026. This space will be intentionally focused on collaborations to help improve the security of the open source supply chain we rely on.

### Do not duplicate

We will rely on improving and/or adapting existing tooling first.

### Meet developers where they develop

Tooling development will focus on ease of use and integration into existing developer pipelines.

### Good is perfect enough

We are not aiming for perfection or analysis/paralysis. We will engage in continuous CI/CD cycles. 

## Supported Tools

The SIG supports multiple initiatives to further its goals. In addition to compiling feedback for ORBIT Technical Initiatives, the SIG provides a reporting structure for ORBIT software projects ("Supported Tools"). On a quarterly basis, the SIG Chair will provide a summary of recent developments on Supported Tools to the ORBIT Technical Steering Committee. New Supported Tools may be added with approval of the ORBIT TSC. In the case of larger projects, additional approval by the OpenSSF Technical Advisory Committee may be required.

| Tool | Lead |
| --- | --- |
| [Minder](https://github.com/mindersec) | Evan Anderson |
| [OSPS Baseline Scanner](https://github.com/ossf/pvtr-github-repo-scanner) | Jason Meridth |
| [SI Tooling](https://github.com/ossf/si-tooling) | Eddie Knight |
| [Gemara MCP Server](https://github.com/gemaraproj/gemara-mcp) | Jenn Power |
| [Gemara SDK for Go](https://github.com/gemaraproj/go-gemara) | Jenn Power |

## Community Consensus

Contributions to the SIG repository may take many forms. It is the responsibility of the Approvers to ensure that all contributions are representative of the greater community.

Community consensus shall be reached when Approvers from more than one organization have affirmed on the contribution pull request that:

- The contributed asset or change has been presented in a publicly announced and accessible community collaboration session (such as a recurring public meeting).
- At least three end user organizations have provided feedback and assent to the contribution. 
- Where applicable, at least two maintainers from impacted tools or technologies have provided feedback and assent to the contribution.
- Approximately two-thirds or more of observed responses to the contribution are in assent.

## Contributor Roles

Contribution proposals are welcome from any person who abides by the OpenSSF Code of Conduct.

Additionally, the SIG is governed by the following roles.

### Approver

An approver is responsible for confirming community consensus, may be elected to Chairperson, and may act as a delegate for the Chairperson as needed.

A new approver may be nominated by any approver after participating in at least three community collaboration sessions.

Nominations must be confirmed by two-thirds of the current Approvers membership in the form of pull request approvals to modify the CODEOWNERS file for the SIG repository. The active Chairperson is responsible for confirming and publicly announcing the new Approver when this threshold has been met.

### Co-Chair

Two Co-Chairs are responsible for running community meetings, resolving disputes, appointing an External Liaison, and confirming new Approvers.

Co-Chairs are asked to also ensure that an active Approver is scheduled to succeed them prior to stepping down. The nomination may be made by any Approver and must be confirmed by two-thirds of the current Approvers in the form of pull request approvals to modify this document.

If a confirmation is not complete upon the departure of a Co-chair, the seat may be filled by decision of the ORBIT Working Group Technical Steering Committee.

One Co-Chair will fill the role of Technical Steering Committee, in accordance with the ORBIT Working Group governance.

#### Current Co-Chairs:

- Nicole Bates (Microsoft), ORBIT TSC Representative
- Sarah Evans (Dell)

#### Chair Emeritus:

- _(None, yet!)_

### Removal and Emeritus

Any role may be forcefully vacated due to non-confidence or absence by two-thirds vote of the Approvers in the form of pull request approvals to modify the relevant document.

Co-Chairs retain Approver status when stepping down unless otherwise specified. Past Co-Chairs are recognized here as recognition of their significant contribution to the community.
