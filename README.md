# Kenneth Chinedu

**DevSecOps · Platform Engineering · Cloud Infrastructure**

[LinkedIn](https://www.linkedin.com/in/kenneth-chinedu-5b1342151/) · [anamsken60@gmail.com](mailto:anamsken60@gmail.com)

I build and secure the platforms that product teams ship on: Kubernetes on AWS and Azure, multi-account cloud governance, GitOps delivery, infrastructure as code, and security controls wired into the pipeline instead of bolted on after. 4+ years running production infrastructure.

What I focus on:

- **Cloud foundations & governance**: AWS Organizations multi-account setups (account structure, SCP guardrails, centralized IAM), and advanced Azure infrastructure
- **Platform engineering**: EKS with Karpenter autoscaling, Istio service mesh, ArgoCD GitOps, multi-environment Terraform/Terragrunt
- **Software supply-chain security**: SAST/SCA gates, SBOMs, image signing and provenance (cosign, SLSA), container hardening
- **Identity & secrets**: OIDC-based CI auth, Vault, least-privilege IAM, environment-scoped secrets
- **Reliability**: SLOs and error budgets, Prometheus/Grafana/Loki observability, chaos experiments with measured outcomes

---

### Selected work

| Project | What it shows |
|---|---|
| [**pygoat DevSecOps pipeline**](https://github.com/kennethchinedu/pygoat) | Security-gated CI/CD on an intentionally vulnerable Django app: Semgrep SAST with a custom rule (+ tests) and fail-on-new gate, Snyk SCA gate, Hadolint, CycloneDX SBOM, cosign keyless signing with SLSA provenance, staging → production deploys with env-scoped secrets. Runtime image cut from 2,989 to 354 OS findings. |
| [**NovaOps Platform**](https://github.com/kennethchinedu/NovaOps-Platform-Project) | Cloud-native platform for staging and production: Terraform modules via Terragrunt, ArgoCD ApplicationSets, Helm + Istio, Cloudflare edge (DNS/WAF), Prometheus/Loki/Grafana/Kiali observability, network policies and IAM. |
| [**Chaos engineering on EKS**](https://github.com/kennethchinedu/Chaos-DevOps-SRE-project) | SLO-driven reliability lab: formal availability/latency SLOs with error budgets, hypothesis-driven Chaos Mesh experiments on EKS + Karpenter + Istio, all infra in Terragrunt. |
| [**Hybrid Kubernetes platform**](https://github.com/kennethchinedu/HE-multi-cloud-hybrid-kubernetes-project) | Self-managed multi-node cluster running Online Boutique: provisioning, GitOps, service mesh, policy enforcement, observability and chaos testing end to end. |
| [**Terraform + Ansible on AWS**](https://github.com/kennethchinedu/end-to-end-devops-ansible-monitoring-cicd-project) | VPC, subnets, security groups and EC2 provisioned with Terraform; Nginx reverse proxy and app configuration with Ansible. |

---

### Stack

**Cloud & IaC** &nbsp; AWS (Organizations, multi-account) · Azure · Terraform · Terragrunt · Ansible  
**Containers & orchestration** &nbsp; Kubernetes (EKS) · Karpenter · Helm · Istio · Docker  
**Delivery** &nbsp; ArgoCD · GitHub Actions · Jenkins  
**Security** &nbsp; Trivy · Semgrep · Snyk · cosign / SLSA · CycloneDX · Vault · OIDC  
**Observability** &nbsp; Prometheus · Grafana · Loki · Alertmanager · ELK  
**Languages** &nbsp; Python · Bash · SQL

### Certifications

<img width="100" height="100" alt="aws-certified-cloud-practitioner" src="https://github.com/user-attachments/assets/b565e424-bdb1-442b-ba16-543b39f1aaa1" />
<img width="100" height="100" alt="aws-certified-solutions-architect-associate" src="https://github.com/user-attachments/assets/e50f53e0-e005-43fb-b204-f29133fc6fcc" />
<img width="100" height="100" alt="Terraform associate" src="https://github.com/user-attachments/assets/faa92624-ed37-4f99-8c35-1d55babab986" />
