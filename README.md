<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,100:3b82f6&height=220&section=header&text=Eric%20Nguyen&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=30&desc=Senior%20AI%20Platform%20Engineer%20%7C%20Agentic%20Platforms%20%7C%20AWS&descSize=18&descAlignY=50&descAlign=50)

<!-- Typing SVG -->
<a href="https://github.com/DenverCoder1/readme-typing-svg">
<img src="https://readme-typing-svg.demolab.com/?lines=The%20man%20who%20automates%20everything;If%20I%20did%20it%20twice%2C%20it's%20getting%20a%20pipeline&font=Fira%20Code&center=true&width=500&height=45&color=58a6ff&vCenter=true&pause=800&duration=3000&size=20" />
</a>

<!-- Social badges -->
<a href="https://eric-n.com">
<img alt="Website" src="https://img.shields.io/badge/eric--n.com-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/eric-nguyenit">
<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-6366f1?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:github-s@eric-n.com">
<img alt="Email" src="https://img.shields.io/badge/Email-3b82f6?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

<!-- Divider 1 -->
<img src="./assets/divider-1.svg" alt="divider" width="100%">

<!-- About Me Section Banner -->
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8b5cf620,50:4a90e220,100:8b5cf620&height=1" width="100%"/>
</div>

## 🚀 About Me

**Senior AI Platform Engineer** building the infrastructure that AI runs on. I design, build, and operate agentic workflow platforms, internal developer portals, and the governed cloud foundations underneath them at enterprise scale.

My actual rule is simpler than that: **if I do it twice, it gets a pipeline.**

**Things I've shipped that moved a number:**
- **3 days → 10 minutes** — AWS account provisioning, by replacing a ClickOps runbook with an agent in Microsoft Teams that vends accounts through HCP Terraform with human-gated approval
- **5,000+ documents, 10+ engineers** — production RAG on Bedrock Knowledge Bases with hybrid retrieval, Cohere reranking, and citation-grounded answers
- **45K+ resources across 200+ AWS accounts** — discovered and scaffolded into Terraform state by a parallel asyncio engine, migrating an org off ClickOps
- **$250K / 9 months** — the agentic workflow platform + internal developer portal I currently own end to end for a Fortune 500 IT org

<!-- Divider 2 -->
<img src="./assets/divider-2.svg" alt="divider" width="100%">

## 🔨 Now

*Updated July 2026*

- Building a central agentic workflow platform so every ops team in the org has one governed place to run agent automation — shared agent, MCP tool-access, and human-approval standards instead of ten teams inventing their own
- Rebuilding my EKS platform to the 2026 golden standard: Karpenter, ArgoCD, and a teardown/spin-up lifecycle cheap enough to run in a personal account → [`eks-golden-platform`](https://github.com/c0debyeric/eks-golden-platform)
- Running local LLMs in the homelab for when the API credits run out — and to keep an honest baseline on what managed inference is actually worth
- Automating my own life to an unreasonable degree: cron-driven morning briefings, an agent-run job-search pipeline, a fitness tracker I wrote instead of downloading

<!-- Divider 2b -->
<img src="./assets/divider-3.svg" alt="divider" width="100%">

## 📊 Stats

<div align="center">

<!-- github-profile-summary-cards + streak-stats, deliberately NOT github-readme-stats:
     that public instance was returning 503 DEPLOYMENT_PAUSED as of 2026-07-24, which
     silently turns every card into a broken-image icon. Every endpoint used here was
     verified returning 200 + image/svg+xml. -->
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=c0debyeric&theme=github_dark" width="100%"/>

<img src="https://streak-stats.demolab.com/?user=c0debyeric&theme=react&background=161b22&border=30363d&ring=9b6dff&fire=9b6dff&currStreakLabel=4a90e2&hide_border=false" height="180"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=c0debyeric&theme=github_dark" height="180"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=c0debyeric&theme=react-dark&bg_color=161b22&color=9b6dff&line=4a90e2&point=ffffff&hide_border=false&border_color=30363d&area=true" width="100%"/>

</div>

<!-- Divider: Now -->
<img src="./assets/divider-2.svg" alt="divider" width="100%">

## 🛠️ Featured Projects

<!-- Plain-markdown cards instead of github-readme-stats pin images: the pin endpoint
     was down (503 DEPLOYMENT_PAUSED) on 2026-07-24, and a dead third-party image is a
     worse first impression than text. This renders forever with zero dependencies. -->

### ⎈ [eks-golden-platform](https://github.com/c0debyeric/eks-golden-platform)
EKS to the 2026 golden standard — Terraform + **Karpenter** + **ArgoCD** GitOps with Prometheus/Grafana/Loki/OpenTelemetry, and a teardown/spin-up lifecycle cheap enough to leave off overnight.
`Terraform` `EKS` `Karpenter` `ArgoCD` `OpenTelemetry`

### 🤖 [crewai-research-pipeline](https://github.com/c0debyeric/crewai-research-pipeline)
Hierarchical **CrewAI** crew (Researcher / Analyst / Editor under a manager agent) on Amazon Bedrock, scheduled on Lambda, delivering briefs to Discord. 100% Terraform-managed, GitHub OIDC.
`CrewAI` `Bedrock` `Lambda` `Terraform` `Python`

### 🔎 [aws-resource-inventory](https://github.com/c0debyeric/aws-resource-inventory)
Org-wide scanner that detects every resource across an AWS Organization — 37+ AWS and 24+ Azure resource types in parallel, OIDC auth, GitHub Actions automation with S3 upload and Teams notifications.
`Python` `AWS Organizations` `GitHub Actions` `OIDC`

### 🗃️ [Terraform-aws-bulk-import](https://github.com/c0debyeric/Terraform-aws-bulk-import)
Rips thousands of unmanaged AWS resources into Terraform state at scale — parallelized across accounts and regions, auditable, zero guesswork.
`Terraform` `Python` `AWS Organizations`

<!-- Divider 3 -->
<img src="./assets/divider-3.svg" alt="divider" width="100%">

## 🏆 Certifications

<div align="center">

[![AWS Solutions Architect](https://images.credly.com/size/100x100/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png)](https://www.credly.com/org/amazon-web-services/badge/aws-certified-solutions-architect-associate)
[![AWS AI Practitioner](https://images.credly.com/size/100x100/images/4d4693bb-530e-4bca-9327-de07f3aa2348/image.png)](https://www.credly.com/org/amazon-web-services/badge/aws-certified-ai-practitioner)
[![AWS GenAI Developer](https://images.credly.com/size/100x100/images/52c6e5ac-9516-4944-a4df-e31b23c9bbf2/blob)](https://www.credly.com/org/amazon-web-services/badge/aws-certified-generative-ai-developer-professional)
[![Azure Administrator](https://images.credly.com/size/100x100/images/336eebfc-0ac3-4553-9a67-b402f491f185/azure-administrator-associate-600x600.png)](https://learn.microsoft.com/en-us/credentials/certifications/azure-administrator/)
[![Terraform Associate](https://images.credly.com/size/100x100/images/0e717fa5-93a1-4203-964c-051b4734b7eb/blob)](https://www.credly.com/badges/hashicorp-certified-terraform-associate-004)

</div>

<!-- Divider 4 -->
<img src="./assets/divider-4.svg" alt="divider" width="100%">

## ⚙️ Tech Stack

<table align="center">
<tr>
<td align="center" width="160"><b>☁️ Cloud & IaC</b></td>
<td align="center">
<img src="https://img.shields.io/badge/AWS-7c3aed?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/>
<img src="https://img.shields.io/badge/Azure-7c3aed?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure"/>
<img src="https://img.shields.io/badge/Terraform-7c3aed?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
<img src="https://img.shields.io/badge/Kubernetes-7c3aed?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
<img src="https://img.shields.io/badge/Docker-7c3aed?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/Ansible-7c3aed?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible"/>
<img src="https://img.shields.io/badge/Packer-7c3aed?style=for-the-badge&logo=packer&logoColor=white" alt="Packer"/>
</td>
</tr>
<tr>
<td align="center"><b>🤖 AI & ML</b></td>
<td align="center">
<img src="https://img.shields.io/badge/Bedrock-6366f1?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="Bedrock"/>
<img src="https://img.shields.io/badge/PyTorch-6366f1?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
<img src="https://img.shields.io/badge/MLflow-6366f1?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow"/>
<img src="https://img.shields.io/badge/CrewAI-6366f1?style=for-the-badge&logoColor=white" alt="CrewAI"/>
<img src="https://img.shields.io/badge/vLLM-6366f1?style=for-the-badge&logoColor=white" alt="vLLM"/>
<img src="https://img.shields.io/badge/n8n-6366f1?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n"/>
</td>
</tr>
<tr>
<td align="center"><b>🔄 CI/CD & GitOps</b></td>
<td align="center">
<img src="https://img.shields.io/badge/GitHub_Actions-4f46e5?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
<img src="https://img.shields.io/badge/ArgoCD-4f46e5?style=for-the-badge&logo=argo&logoColor=white" alt="ArgoCD"/>
<img src="https://img.shields.io/badge/Helm-4f46e5?style=for-the-badge&logo=helm&logoColor=white" alt="Helm"/>
<img src="https://img.shields.io/badge/GitLab_CI-4f46e5?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab CI"/>
</td>
</tr>
<tr>
<td align="center"><b>📊 Observability</b></td>
<td align="center">
<img src="https://img.shields.io/badge/Prometheus-3b82f6?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus"/>
<img src="https://img.shields.io/badge/Grafana-3b82f6?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/>
<img src="https://img.shields.io/badge/OpenTelemetry-3b82f6?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry"/>
</td>
</tr>
<tr>
<td align="center"><b>💻 Languages</b></td>
<td align="center">
<img src="https://img.shields.io/badge/Python-2563eb?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Bash-2563eb?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash"/>
<img src="https://img.shields.io/badge/Flutter-2563eb?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
</td>
</tr>
</table>

<div align="center">

<a href="https://eric-n.com/resume/Eric_Nguyen_Resume.pdf">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,100:3b82f6&height=120&section=footer&text=📄%20Download%20My%20Resume&fontSize=20&fontColor=ffffff&fontAlignY=65&animation=fadeIn" alt="Download My Resume" width="100%"/>
</a>

</div>
<!-- Stats updated on 2026-07-19 02:54:44 UTC -->
