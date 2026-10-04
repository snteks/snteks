<!--
  HOW TO USE: Create a public repo named exactly like your GitHub username
  (e.g. github.com/janedoe/janedoe). Save this file as README.md in it.
  Replace every [BRACKET]. Delete this comment.
-->

# Hi, I'm Sreeram Pasham 👋

**Freelance Cloud Architect & DevSecOps Engineer**

I design and build secure, compliance-ready platforms on AWS: multi-account architecture, Kubernetes (EKS) platforms, identity federation, and Infrastructure as Code with security built into the pipeline.

📍 Chantilly / Remote · 📫 devopseng@snteks.com · 🔗 [LinkedIn] · 🌐 [website, optional]
🟢 **Currently available for freelance projects** (30hours/week, starting ASAP)

---

## What I help with

| | |
|---|---|
| ☁️ **Cloud architecture** | Multi-account AWS design, VPC / Transit Gateway networking, private-by-default connectivity, CloudFront + WAF edge delivery |
| 🔐 **DevSecOps** | Policy as code, zero-secret-in-git, OIDC-federated CI/CD, least-privilege IAM, NIST 800-53 control mapping |
| ☸️ **Platform engineering** | EKS, Cilium, Gateway API, Karpenter, ArgoCD GitOps |
| 🧱 **Infrastructure as Code** | OpenTofu / Terraform, Terragrunt, reusable module libraries |
| 🪪 **Identity & access** | Entra ID SAML federation, ABAC, permission boundaries, delegated IAM admin |
| 🤖 **AI infrastructure** | Secure, budget-controlled LLM gateways and private LLM-powered applications on Amazon Bedrock |

---

## Featured projects

> Reference implementations built from scratch to demonstrate patterns I use in production. No client code or data.

| Project | What it shows |
|---|---|
| [**aws-multi-tenant-platform-reference**]([REPO URL]) | OpenTofu + Terragrunt multi-account platform: EKS with Cilium, Transit Gateway, Network Firewall, Entra ID SAML → AWS with ABAC role elevation and permission boundaries, and OIDC-based CI/CD with drift detection |
| [**platform-gitops-reference**]([REPO URL]) | Multi-tenant ArgoCD GitOps: tenant-isolated AppProjects and ApplicationSets, gated dev → prod promotion, Karpenter node pools, and Kyverno policy enforcement |
| [**litellm-bedrock-gateway-eks**]([REPO URL]) | LLM gateway on EKS with per-user budgets, rate limits, and IRSA scoped to specific Bedrock models |
| [**aws-private-llm-app-reference**]([REPO URL]) | CloudFront + WAF in front of a fully private ALB (VPC Origins), NAT-free Fargate, Bedrock over VPC endpoints, Cognito PKCE, and a Step Functions refresh pipeline |
| [**aws-private-egress-network-firewall**]([REPO URL]) | Zero-internet-egress workloads with domain-allowlisted Network Firewall and SSM-only access |
| [**jira-dc-aws-iac-reference**]([REPO URL]) | Terraform + Ansible deployment with WAFv2, KMS everywhere, SSM-only access, and a parallel-standup migration with rollback |

---|---|
| [**eks-gitops-platform-reference**]([REPO URL]) | OpenTofu + Terragrunt EKS platform with Cilium default-deny, Pod Security restricted, External Secrets, and ArgoCD App-of-Apps |
| [**aws-saml-abac-federation**]([REPO URL]) | Entra ID → standalone AWS accounts with session-tag ABAC, permission boundaries, and session-revocation automation |
| [**litellm-bedrock-gateway-eks**]([REPO URL]) | LLM gateway on EKS with per-user budgets, rate limits, and IRSA scoped to specific Bedrock models |
| [**github-actions-oidc-terraform**]([REPO URL]) | Reusable workflows: OIDC auth, plan/apply, drift detection with auto-issues, canary-gated rollouts |
| [**aws-private-egress-network-firewall**]([REPO URL]) | Zero-internet-egress workloads with domain-allowlisted Network Firewall and SSM-only access |
| [**aws-private-llm-app-reference**]([REPO URL]) | CloudFront + WAF in front of a fully private ALB (VPC Origins), NAT-free Fargate, Bedrock over VPC endpoints, Cognito PKCE, and a Step Functions refresh pipeline |

---

## Toolbox

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?style=flat&logo=opentofu&logoColor=black)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Cilium](https://img.shields.io/badge/Cilium-F8C517?style=flat&logo=cilium&logoColor=black)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Also:** Terragrunt · Kustomize · Helm · Kyverno · External Secrets Operator · Karpenter · Prometheus / Grafana · Bash

---

## Principles I build by

- **Secure by default:** default-deny networking, least-privilege IAM, no secrets in git
- **Everything as code:** reproducible, reviewable, and drift-detected
- **Rollback before rollout:** every cutover has a tested way back
- **Leave it runnable:** runbooks and decision records ship with the system

---

## Let's work together

I take on architecture reviews, platform builds, DevSecOps hardening, and migrations.
👉 **[email]** or [book a call]([CALENDAR LINK])
