# Hi, I'm Juan De Sousa.

### Senior Platform Engineer | Kubernetes · Terraform · GitOps · Cloud Reliability

I build and operate cloud platforms that help engineering teams deploy, recover, and maintain production services with confidence. I bring **10+ years of experience in IT**, hands-on infrastructure ownership, and technical leadership working directly with CTOs.

**Based in Caracas, Venezuela (UTC−4).**

[LinkedIn](https://linkedin.com/in/juanmdsousa/) · [Email](mailto:juanmdsousa@gmail.com)

## What I bring to a platform team

- **Platform ownership:** Built an Azure production platform from the ground up with AKS and infrastructure automation, covering delivery workflows and ongoing operations.
- **Developer enablement:** Designed component-specific CI/CD pipelines and FluxCD GitOps workflows to make deployments repeatable and changes reviewable. Previous experience includes Jenkins delivery workflows on AWS.
- **Architecture and migration leadership:** Led cloud migration initiatives directly with CTOs and maintained technical continuity through CTO transitions.
- **Infrastructure as Code:** Used Terraform to reproduce an enterprise architecture for a Badgr deployment, translating infrastructure requirements into repeatable configuration.
- **AI infrastructure:** Deployed and operated GPU-backed LLM services on Kubernetes.
- **Security and operations:** Implemented infrastructure controls supporting SOC 2 examinations, connecting platform configuration with operational practices and evidence.

## Featured engineering projects

### [Disaster Recovery Lab](https://github.com/yoaoxd/disaster-recovery-lab)

A reproducible **PostgreSQL recovery lab** built around the question: can a backup actually restore usable data after a failure? It implements data-loss, service-loss, and corrupted-backup scenarios using disposable Docker containers and synthetic data.

- Logical backups with `pg_dump`, clean-room restores with `pg_restore`, and SHA-256 archive integrity checks.
- Exact baseline comparisons, an expected post-backup data-loss check, and a database write probe.
- Database-level recovery-time and recovery-point-age measurements against configurable targets, with JSON evidence reports.
- Documented operator runbook, recovery tradeoffs, and explicit validation limits.

**Demonstrates:** recovery engineering · PostgreSQL · Python · Docker · RTO/RPO reasoning · operational documentation. This is a local reference lab; production failover and end-to-end service recovery are outside its implemented scope. See the repository for validation status.

### [SOC2 Compliancer](https://github.com/yoaoxd/soc2-compliancer)

A multi-cloud platform for infrastructure control analysis and Terraform bundle generation. Combines a Go API and React dashboard with AWS, Azure, and GCP modules, control mappings, scan history, and reviewable remediation proposals.

**Demonstrates:** Terraform · cloud security · SOC 2 control mapping · Go · multi-cloud architecture.

| Project | Engineering focus |
| --- | --- |
| [GitOps Developer Platform](https://github.com/yoaoxd/gitops-developer-platform) | Kubernetes service scaffolding, optional Flux resources, and Git-based rollback guidance. |
| [Infrastructure Drift Monitor](https://github.com/yoaoxd/infrastructure-drift-monitor) | Python CLI reporting recorded drift and proposed changes from Terraform JSON plans. |
| [LLM Inference Platform](https://github.com/yoaoxd/llm-inference-platform) | Kubernetes manifests for GPU inference and compute-cost estimates from supplied rates. |
| [Cloud Reliability Lab](https://github.com/yoaoxd/cloud-reliability-lab) | SQLite backup and restore, request-based SLO reports, and recovery runbooks. |
| [AI DevOps Prompts](https://github.com/yoaoxd/ai-devops-prompts) | Reusable prompts for CI/CD reviews, testing, and troubleshooting, with a worked example and evaluation criteria. |

These are independent reference implementations. Each repository documents its scope, design decisions, and validation limits.

## Core technologies

**Platform:** Kubernetes · AKS · Docker · Helm · Linux  
**Infrastructure automation:** Terraform · Ansible · Python · Bash  
**Delivery:** GitHub Actions · FluxCD · Jenkins · ArgoCD · Git  
**Cloud:** Microsoft Azure · AWS · Google Cloud · Oracle Cloud Infrastructure  
**Data and workloads:** PostgreSQL · Redis · GPU-backed LLM inference

## Products I build

- **[GeoVZ](https://geovz.com):** A web geography game focused on Venezuela, combining real-world imagery, location discovery, and competitive play. Source code is private.
- **[Planea](https://web.planea.chat):** An AI-assisted local discovery and planning platform for businesses, services, and events in Caracas. Source code is private.

## Let's connect

I'm interested in teams that need an engineer who can own platform architecture, improve delivery workflows, and carry changes through production operations.

- **Location:** Caracas, Venezuela · UTC−4, aligned with U.S. East Coast working hours.
- **Opportunities:** Remote Senior Platform Engineer roles and long-term international contractor engagements with U.S. companies.
- **Languages:** Spanish · English · Portuguese.
- **Contact:** [LinkedIn](https://linkedin.com/in/juanmdsousa/) · [juanmdsousa@gmail.com](mailto:juanmdsousa@gmail.com).

Professional contributions from the past two years also appear under my dedicated work account, [@jdesousa-bc](https://github.com/jdesousa-bc).
