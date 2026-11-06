<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=170&color=0:0f172a,55:1e3a8a,100:2563eb&text=Abdullatif%20Karimov&fontColor=ffffff&fontSize=44&fontAlignY=38&desc=Backend%20Developer%20%E2%86%92%20DevOps%20Engineer&descAlignY=58&descSize=17" alt="Abdullatif Karimov — Backend Developer and DevOps Engineer" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2563EB&center=true&vCenter=true&width=640&lines=Building+backends+with+Python+%26+Django;From+first+commit+to+production;Docker+%C2%B7+CI%2FCD+%C2%B7+Self-hosted+servers" alt="Building backends with Python and Django. From first commit to production. Docker, CI/CD, self-hosted servers."/>

📍 Samarkand, Uzbekistan 🇺🇿

<a href="https://t.me/Karimov_Abdullatif"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"/></a>
<a href="mailto:abdullatifkarimov772@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://gitlab.com/KarimovProject/"><img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white" alt="GitLab"/></a>
<a href="https://instagram.com/k.abdullatif.2003"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram"/></a>
<a href="https://www.codewars.com/users/KarimovProject/"><img src="https://img.shields.io/badge/Codewars-B1361E?style=flat-square&logo=codewars&logoColor=white" alt="Codewars"/></a>

</div>

## About

I build backend systems with Python and Django, then take them all the way to production: containers, CI/CD, reverse proxies and backups on servers I set up myself.

I've been writing code since 2017, starting with Pascal at school. I hold a Bachelor's in Computer Engineering from TUIT and went through the DevOps track at School 21.

## My journey

```mermaid
timeline
    2017 : First lines of code in Pascal
    2019 : C++ and competitive problems at the IT lyceum
    2021 : Python, Computer Engineering at TUIT
    2023 : Django REST Framework and Docker
    2024 : DevOps track at School 21
    2026 : Production systems on my own server
```

## Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=python,django,postgres,redis,sqlite,cpp&perline=6" alt="Python, Django, PostgreSQL, Redis, SQLite, C++"/>
</p>
<p>
  <img src="https://skillicons.dev/icons?i=docker,linux,ubuntu,bash,nginx,githubactions,gitlab,git&perline=8" alt="Docker, Linux, Ubuntu, Bash, Nginx, GitHub Actions, GitLab, Git"/>
</p>

## Selected work

| Project | What it is | Built with |
|---|---|---|
| **K-ONE** · private | Event management system: planning, approvals, QR check-in, reports, Telegram notifications | Django, PostgreSQL, Redis, Docker |
| [**Oncoscience**](https://github.com/KarimovProject/Journal_cancercenter) | Academic journal platform for an oncology center, in three languages | Django, DRF, PostgreSQL |
| [**Portfolio**](https://github.com/KarimovProject/portfolio) | My personal site | HTML |

## How I ship

The deploy pipeline behind K-ONE: nothing reaches production without green tests, and a failed release rolls itself back.

```mermaid
flowchart LR
    A[git push] --> B[CI: lint and tests]
    B -->|green| C[Move deploy branch]
    C --> D[Server pulls the release]
    D --> E[Database backup]
    E --> F[Build and start containers]
    F --> G{Health check}
    G -->|healthy| H[Live]
    G -->|failed| I[Automatic rollback]
```

## Now learning

Monitoring with Prometheus and Grafana, then Kubernetes and Terraform.

## GitHub activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=KarimovProject&theme=transparent&hide_border=true&ring=2563EB&fire=2563EB&currStreakLabel=2563EB" alt="GitHub streak"/>

<img src="https://ghchart.rshah.org/2563eb/KarimovProject" alt="GitHub contribution chart" width="100%"/>

</div>
