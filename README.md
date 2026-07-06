<div align="center">

<img src="assets/hero.svg" width="100%" alt="Deplyra — DevOps & Platform Engineering. Build it as code, ship it with GitOps, run it to SLOs." />

<br/>

### A DevOps &amp; platform-engineering studio.
**We build production infrastructure as code, ship it with GitOps, and run it to SLOs** — so your team ships faster, sleeps better, and owns a platform that runs without us.

[![Website](https://img.shields.io/badge/deplyra.com-53E8D4?style=for-the-badge&logo=cloudflare&logoColor=0E1B2A)](https://deplyra.com)
[![Contact](https://img.shields.io/badge/Abdullah%40deplyra.com-0E1B2A?style=for-the-badge&logo=maildotru&logoColor=53E8D4)](mailto:Abdullah@deplyra.com)
[![LinkedIn](https://img.shields.io/badge/Deplyra-0E1B2A?style=for-the-badge&logo=linkedin&logoColor=53E8D4)](https://linkedin.com/company/deplyra)

<img src="assets/divider.svg" width="100%" alt="" />

</div>

## 🛰️ What we do

<table>
<tr>
<td width="33%" valign="top">

### ☁️ Cloud &amp; IaC
Terraform / Terragrunt landing zones on **AWS · Azure · GCP** — reviewed in PRs, policy-gated, reproducible from scratch.

</td>
<td width="33%" valign="top">

### ⎈ Kubernetes &amp; GitOps
Production **EKS / AKS / GKE** delivered with Argo CD app-of-apps, keyless OIDC pipelines, autoscaling and zero-downtime rollouts.

</td>
<td width="33%" valign="top">

### 🔐 DevSecOps
Supply-chain security wired into the pipeline — SBOMs, keyless **Cosign** signing, SLSA provenance, **Kyverno** admission gates. Unsigned never ships.

</td>
</tr>
<tr>
<td valign="top">

### 📈 Observability &amp; SLOs
**Prometheus · Grafana · Loki · Tempo · OTel** — golden signals, error budgets, multi-burn-rate alerts. Dashboards as code.

</td>
<td valign="top">

### 🕸️ DevNetOps
Network as code, service mesh + mTLS, zero-trust connectivity over encrypted meshes — nothing sensitive on public NICs.

</td>
<td valign="top">

### 🧭 GRC — as code
CIS baselines, kube-bench, OPA/Kyverno policy — controls enforced in CI and continuous evidence generated for audits.

</td>
</tr>
</table>

<div align="center"><img src="assets/divider.svg" width="100%" alt="" /></div>

## 📐 Featured platforms

> Every repo is documented like a handover — architecture, decisions, trade-offs, and how to run (and destroy) it. **Open the code before you hire us.**

| # | Platform | What it proves | Stack |
|:-:|----------|----------------|-------|
| 01 | **[eks-gitops-platform](https://github.com/deplyra/eks-gitops-platform)** | Production EKS delivered the GitOps way — app-of-apps, keyless OIDC CI/CD, IRSA, External Secrets, supply-chain scanning | `Terraform` `EKS` `Argo CD` `Helm` |
| 02 | **[multicloud-terraform-landing-zone](https://github.com/deplyra/multicloud-terraform-landing-zone)** | Self-service compliant infrastructure across two clouds — policy-as-code + cost checks on every PR | `Terraform` `Terragrunt` `AWS` `Azure` `OPA` |
| 03 | **[observability-slo-platform](https://github.com/deplyra/observability-slo-platform)** | Metrics, logs &amp; traces wired into multi-burn-rate SLO alerting with error budgets — dashboards as code | `Prometheus` `Grafana` `Loki` `Tempo` `OTel` |
| 04 | **[devsecops-supply-chain](https://github.com/deplyra/devsecops-supply-chain)** | A supply chain where unsigned images physically can't ship — SBOMs, keyless signing, SLSA provenance, admission gates | `Trivy` `Cosign` `Kyverno` `SLSA` |

<div align="center"><img src="assets/divider.svg" width="100%" alt="" /></div>

## 🗺️ How every engagement runs

```
  01 · DISCOVERY        02 · BUILD            03 · SHIP             04 · RUN & HAND OVER
  ─────────────         ─────────────        ─────────────         ─────────────────────
  Design doc +          Infra, pipelines     GitOps delivery,      SLO monitoring,
  architecture,         & dashboards as      zero-downtime         on-call runbooks,
  approved before       code — reviewed,     releases, auto        full handover.
  any code.             secured by default.  rollback.             It runs without us.
```

<div align="center"><img src="assets/divider.svg" width="100%" alt="" /></div>

## 🧰 The stack we run in production

<div align="center">

![AWS](https://img.shields.io/badge/AWS-0E1B2A?style=flat-square&logo=amazonwebservices&logoColor=53E8D4)
![Azure](https://img.shields.io/badge/Azure-0E1B2A?style=flat-square&logo=microsoftazure&logoColor=53E8D4)
![GCP](https://img.shields.io/badge/GCP-0E1B2A?style=flat-square&logo=googlecloud&logoColor=53E8D4)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0E1B2A?style=flat-square&logo=kubernetes&logoColor=53E8D4)
![Docker](https://img.shields.io/badge/Docker-0E1B2A?style=flat-square&logo=docker&logoColor=53E8D4)
![Terraform](https://img.shields.io/badge/Terraform-0E1B2A?style=flat-square&logo=terraform&logoColor=53E8D4)
![Terragrunt](https://img.shields.io/badge/Terragrunt-0E1B2A?style=flat-square&logo=terraform&logoColor=53E8D4)
![Ansible](https://img.shields.io/badge/Ansible-0E1B2A?style=flat-square&logo=ansible&logoColor=53E8D4)
![Argo CD](https://img.shields.io/badge/Argo_CD-0E1B2A?style=flat-square&logo=argo&logoColor=53E8D4)
![Helm](https://img.shields.io/badge/Helm-0E1B2A?style=flat-square&logo=helm&logoColor=53E8D4)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0E1B2A?style=flat-square&logo=githubactions&logoColor=53E8D4)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-0E1B2A?style=flat-square&logo=gitlab&logoColor=53E8D4)
![Prometheus](https://img.shields.io/badge/Prometheus-0E1B2A?style=flat-square&logo=prometheus&logoColor=53E8D4)
![Grafana](https://img.shields.io/badge/Grafana-0E1B2A?style=flat-square&logo=grafana&logoColor=53E8D4)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-0E1B2A?style=flat-square&logo=opentelemetry&logoColor=53E8D4)
![Trivy](https://img.shields.io/badge/Trivy-0E1B2A?style=flat-square&logo=aquasecurity&logoColor=53E8D4)
![Cosign](https://img.shields.io/badge/Cosign-0E1B2A?style=flat-square&logo=sigstore&logoColor=53E8D4)
![Kyverno](https://img.shields.io/badge/Kyverno-0E1B2A?style=flat-square&logo=kubernetes&logoColor=53E8D4)
![Python](https://img.shields.io/badge/Python-0E1B2A?style=flat-square&logo=python&logoColor=53E8D4)
![Linux](https://img.shields.io/badge/Linux-0E1B2A?style=flat-square&logo=linux&logoColor=53E8D4)

</div>

<div align="center">

<br/>

## 🚀 Let's build something that stays up

**One message.** We'll reply with questions, not a sales pitch — then a plan you can hold us to.
Remote worldwide · freelance / contract · start immediate.

[![Start a project](https://img.shields.io/badge/Start_a_project-53E8D4?style=for-the-badge&logo=rocket&logoColor=0E1B2A)](https://deplyra.com/contact)
[![Website](https://img.shields.io/badge/deplyra.com-0E1B2A?style=for-the-badge&logo=googlechrome&logoColor=53E8D4)](https://deplyra.com)
[![Email](https://img.shields.io/badge/Abdullah%40deplyra.com-0E1B2A?style=for-the-badge&logo=maildotru&logoColor=53E8D4)](mailto:Abdullah@deplyra.com)

<br/>

<img src="assets/footer.svg" width="100%" alt="Deplyra — build it as code, ship it with GitOps." />

</div>
