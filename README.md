<!-- HEADER — self-hosted SVG in your own repo, always loads -->
<p align="center">
  <img src="https://raw.githubusercontent.com/ArnavSharma03/ArnavSharma03/main/header.svg" width="100%" alt="Arnav Sharma — Cloud & Infrastructure Engineer"/>
</p>

<!-- BADGES — shields.io only, never breaks -->
<p align="center">
  <a href="https://www.linkedin.com/in/arnavsharma03/">
    <img src="https://img.shields.io/badge/LinkedIn-arnavsharma03-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:arnav18503@gmail.com">
    <img src="https://img.shields.io/badge/Email-arnav18503@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=ArnavSharma03&style=for-the-badge&color=00d4ff&label=PROFILE+VIEWS" alt="Profile Views"/>
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-3FB950?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Open to Work"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-IaC_Multi--Cloud-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/ECS_%2B_ECR-Containers-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/FinOps-55--65%25_Cost_Saved-F7A800?style=flat-square"/>
  <img src="https://img.shields.io/badge/Security-GuardDuty_%7C_Macie_%7C_IAM-3FB950?style=flat-square&logo=amazonaws&logoColor=white"/>
</p>

<br/>

---

## 👨‍💻 About Me

```
╔══════════════════════════════════════════════════════════════╗
║         arnav@aws-cloud:~$ cat engineer.profile              ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  ☁  Role     →  Infrastructure Engineer @ Wissenhive        ║
║  📍 Location →  Dehradun, India  🇮🇳                         ║
║  🏆 Cert     →  AWS Certified Solutions Architect (SAA-C03) ║
║  ⚡ Stack    →  Terraform · ECS · ECR · VPC · IAM · Python  ║
║  💸 Impact   →  55–65% cloud cost reduction in production    ║
║  🔒 Security →  GuardDuty · Macie · CloudTrail · IAM LLP    ║
║  🌐 Clouds   →  AWS (Expert) · Oracle Cloud · Azure         ║
║  🟢 Status   →  Available for Cloud / DevOps / SRE roles    ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝

arnav@aws-cloud:~$ echo $MISSION
"Don't just provision infra. Architect systems that scale,
 stay secure, and never waste a dollar."
```

<br/>

---

## ☁️ Infrastructure I Architect & Own

```
                ┌──────────── AWS CLOUD ──────────────────────────┐
                │                                                  │
  USERS ──────► [Route 53] ──► [CloudFront CDN]                   │
                │                      │                           │
                │             [WAF / Shield]                       │
                │                      │                           │
                │         [Application Load Balancer]             │
                │                      │                           │
                │  ┌───────────────────┴──────────────────────┐   │
                │  │          VPC  (Multi-AZ Design)          │   │
                │  │                                          │   │
                │  │  [Public Subnet]     [Private Subnet]    │   │
                │  │   NAT Gateway         ECS Cluster        │   │
                │  │   Bastion Host        ECR Registry       │   │
                │  │   IGW                 Auto Scaling       │   │
                │  │        │                    │            │   │
                │  │        └──────► [RDS / ElastiCache]      │   │
                │  │                                          │   │
                │  │   [VPC Endpoints] ──────────► S3 / ECR  │   │
                │  │   [VPC Peering]   ──────────► Other VPCs│   │
                │  └──────────────────────────────────────────┘   │
                │                                                  │
                │  OBSERVABILITY  │  SECURITY     │  COST OPS     │
                │  CloudWatch     │  GuardDuty    │  Budgets       │
                │  CloudTrail     │  Macie        │  Cost Alloc.   │
                │  X-Ray          │  IAM (LLP)    │  Res. Inst.    │
                │                                                  │
                │        ⚡  PROVISIONED BY TERRAFORM  ⚡          │
                └──────────────────────────────────────────────────┘
```

<br/>

---

## 🏆 Production Impact

<div align="center">

| ⚡ What I Did | 🔧 How | 📈 Result |
|:---|:---|:---:|
| Cloud billing ownership | Reserved Instances + EC2 right-sizing + idle cleanup | **55–65% cost saved** |
| NAT Gateway elimination | VPC Endpoints + VPC Peering | **40%+ cost cut** |
| Enterprise uptime | MSP360 + Zabbix + incident response | **99% uptime SLA** |
| Infrastructure automation | Terraform IaC — AWS + Oracle Cloud | **Zero manual errors** |
| Security hardening | IAM LLP + GuardDuty + Macie + CloudTrail | **Full audit posture** |
| Container workloads | ECS task defs + auto-scaling + health checks | **Zero-downtime deploys** |

</div>

<br/>

---

## 💼 Experience

<details open>
<summary><b>🔧 Infrastructure Engineer — Wissenhive E-Learning &nbsp;|&nbsp; Apr 2026 – Present · Remote</b></summary>
<br>

```terraform
resource "wissenhive" "production" {
  # What I own and operate every single day
  billing_ownership = "Full AWS lifecycle — tagging, allocation, RI planning"
  cost_result       = "55-65% reduction across multi-account environments"
  iac               = "Terraform — AWS + Oracle Cloud, zero manual provisioning"
  containers        = "ECS + ECR — task defs, auto-scaling, health monitoring"
  security          = ["IAM least-privilege", "GuardDuty", "CloudTrail", "Macie"]
  networking        = "VPC Endpoints + Peering → 40%+ NAT Gateway cost savings"
  workload_type     = "zero-downtime production microservices"
}
```

</details>

<details>
<summary><b>🏛️ Cloud Architect Intern — Wissenhive E-Learning &nbsp;|&nbsp; Dec 2025 – Mar 2026 · Remote</b></summary>
<br>

- 🏗️ Architected full AWS production stack — EC2, S3, VPC, IAM, CloudWatch — **AWS Well-Architected Framework**
- 🌐 Multi-account VPC design — NAT costs cut **40%+** via VPC Endpoints & Peering
- 💸 Delivered **55–65% cloud cost reduction** via right-sizing, Reserved Instances, idle cleanup

</details>

<details>
<summary><b>🛡️ Cloud Support Engineer — OneUp Networks &nbsp;|&nbsp; Sep 2025 – Dec 2025 · Remote</b></summary>
<br>

- ⏱️ Maintained **99% uptime SLA** for US enterprise clients — QuickBooks, Thomson Reuters
- 📊 MSP360 + Zabbix monitoring · Windows cloud VM management · RDP incident response

</details>

<br/>

---

## 🛠️ Tech Stack

<div align="center">

**☁️ Cloud Platforms**

![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**⚙️ Core AWS Services**

![EC2](https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![ECS](https://img.shields.io/badge/ECS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![ECR](https://img.shields.io/badge/ECR-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-8C4FFF?style=for-the-badge&logo=amazonaws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white)
![GuardDuty](https://img.shields.io/badge/GuardDuty-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![CloudTrail](https://img.shields.io/badge/CloudTrail-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Macie](https://img.shields.io/badge/Macie-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Auto Scaling](https://img.shields.io/badge/Auto_Scaling-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

**🏗️ IaC & Containers**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

**💻 Languages & Ops Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=for-the-badge&logo=zabbix&logoColor=white)
![Veeam](https://img.shields.io/badge/Veeam-00B336?style=for-the-badge&logo=veeam&logoColor=white)

</div>

<br/>

---

## 🏅 Certifications

<div align="center">

![AWS SAA](https://img.shields.io/badge/AWS_Solutions_Architect-Associate_SAA--C03-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Duke](https://img.shields.io/badge/Cloud_Virtualization_%26_Containers-Duke_University-012169?style=for-the-badge&logo=coursera&logoColor=white)
![Alberta](https://img.shields.io/badge/Agile_%26_Software_Processes-Univ._of_Alberta-00693E?style=for-the-badge&logo=coursera&logoColor=white)

</div>

<br/>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=ArnavSharma03&show_icons=true&theme=github_dark&hide_border=true&title_color=00d4ff&icon_color=f7a800&text_color=c9d1d9&bg_color=0d1117&count_private=true&include_all_commits=true&rank_icon=github" alt="GitHub Stats"/>
<img width="49%" src="https://streak-stats.demolab.com/?user=ArnavSharma03&theme=github-dark-blue&hide_border=true&ring=f7a800&fire=00d4ff&currStreakLabel=f7a800&background=0d1117&sideNums=c9d1d9&sideLabels=8b949e&dates=8b949e" alt="Streak Stats"/>

<img src="https://github-profile-trophy.vercel.app/?username=ArnavSharma03&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=6" alt="Trophies"/>

</div>

<br/>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ArnavSharma03/ArnavSharma03/blob/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/ArnavSharma03/ArnavSharma03/blob/output/github-contribution-grid-snake.svg"/>
  <img alt="Contribution Snake" src="https://github.com/ArnavSharma03/ArnavSharma03/blob/output/github-contribution-grid-snake-dark.svg"/>
</picture>

</div>

<br/>

---

## 📡 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Open_to_Cloud_%2F_DevOps_%2F_SRE_Roles-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arnavsharma03/)
[![Email](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arnav18503@gmail.com)

*📍 Dehradun, India &nbsp;·&nbsp; ☁️ AWS-Certified Infrastructure Engineer &nbsp;·&nbsp; 🟢 Open to Cloud / DevOps / SRE roles*

</div>

---

<div align="center">

`⚡ Built with Terraform · Monitored with CloudWatch · Secured with IAM · Optimised Obsessively ⚡`

</div>
