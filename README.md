<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img alt="kubectl describe engineer lucas-pinheiro-alves: SRE / DevOps Engineer, Cloud & Platform. Status: Ready." src="./assets/banner-light.svg" width="100%">
</picture>

### I keep production boring.

SRE / DevOps engineer with 10+ years in IT and 5+ in cloud. I run high-criticality infrastructure where downtime is not an option. I build observability that pages for the right reasons, automate the toil away, and write the post-mortem so it never happens twice.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-lucas--alvesp-0A66C2?style=flat-square)](https://www.linkedin.com/in/lucas-alvesp/)
![Open to remote](https://img.shields.io/badge/Open_to-remote_SRE_%C2%B7_DevOps_%C2%B7_Platform-3fb950?style=flat-square)

🇧🇷 [Leia em português](./README.pt-BR.md)

## 📈 Impact

| | |
|---|---|
| **5,000 servers** migrated from CentOS to Oracle Linux | Ansible playbooks cut the team from 10 people to 2 and the timeline from 1 year to 2 months |
| **140 domains** with SSL/TLS on autopilot | Certificate lifecycle automation removed a whole class of expiry incidents |
| **5,000+ servers and services** observable | Dashboards, actionable alerts and SLOs, end to end |
| **CI/CD platform migration** | Repos and pipelines moved between platforms with scripted migration, validation and docs |

## 🌱 Open source

**13 merged PRs** in [**habblaud**](https://github.com/marmottajr/habblaud) (⭐ 400+), a TypeScript virtual office for AI coding agents. Each one small and focused, with a regression test or a before/after measurement.

- **CI & supply chain:** the project's first CI workflow on GitHub Actions ([#17](https://github.com/marmottajr/habblaud/pull/17)), Dependabot for npm, Docker and Actions ([#75](https://github.com/marmottajr/habblaud/pull/75)), base image pinned by digest ([#93](https://github.com/marmottajr/habblaud/pull/93)) and the container's in-memory `/tmp` capped at 64 MB ([#94](https://github.com/marmottajr/habblaud/pull/94)).
- **Reliability:** transcript rotation when the OS reuses an inode ([#14](https://github.com/marmottajr/habblaud/pull/14)), files rewritten in place ([#90](https://github.com/marmottajr/habblaud/pull/90)), a permission-queue tie within the same millisecond ([#88](https://github.com/marmottajr/habblaud/pull/88)) and the daily wait limit ([#89](https://github.com/marmottajr/habblaud/pull/89)).
- **UI:** usage cards no longer cover the toolbar ([#87](https://github.com/marmottajr/habblaud/pull/87)), mobile top-bar and "My day" fixes ([#91](https://github.com/marmottajr/habblaud/pull/91), [#92](https://github.com/marmottajr/habblaud/pull/92)), toasts above the timelapse bar ([#85](https://github.com/marmottajr/habblaud/pull/85)).
- **Docs:** Portuguese contribution guide ([#46](https://github.com/marmottajr/habblaud/pull/46)).

🔄 **In review:** OpenCode and Antigravity support (live events, approvals, messages, usage), split into 9 stacked PRs ([#47](https://github.com/marmottajr/habblaud/pull/47), [#76–#83](https://github.com/marmottajr/habblaud/pulls?q=is%3Apr+is%3Aopen+author%3Alpalvess)), and the app version in the window title for [tobi/disktree#83](https://github.com/tobi/disktree/pull/83).

## 🛠️ Projects

- **Chronos** *(personal project)* — Windows widget for monitoring Claude Code usage across Windows and WSL accounts, built with Rust, Tauri 2 and TypeScript.
- [**sourced-postmortem**](https://github.com/lpalvess/sourced-postmortem) — Python verifier that checks incident postmortems against logs and metrics, validates timelines and action items, and runs in Docker without network access.
- [**sourced-carousel**](https://github.com/lpalvess/sourced-carousel) — Generates PDF/PNG carousels with a validation step that checks slide numbers against supplied facts, running in an offline container. *Plugin submitted to Anthropic; awaiting approval.*
- [**study-loop**](https://github.com/lpalvess/study-loop-skill) — AI coding assistant skill for active recall, flashcards and spaced repetition, with local Python storage.

**Security & quality in practice:** dependency updates with Dependabot, digest-pinned container images, offline execution and credential redaction; unit and regression tests with Vitest, plus end-to-end tests with Playwright.

## 🧰 Toolbox

| | |
|---|---|
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square) ![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) |
| **Containers** | ![Kubernetes](https://img.shields.io/badge/Kubernetes_%28EKS,_OKE%29-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) |
| **Languages** | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white) |
| **Desktop & frontend** | ![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **IaC & automation** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) |
| **CI/CD** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) |
| **AI-assisted engineering** | ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white) ![OpenAI Codex](https://img.shields.io/badge/OpenAI_Codex-412991?style=flat-square) ![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white) ![OpenCode](https://img.shields.io/badge/OpenCode-211E1E?style=flat-square) ![Antigravity](https://img.shields.io/badge/Antigravity-4285F4?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white) |
| **Testing & QA** | ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) |
| **Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square) ![ELK](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticsearch&logoColor=white) ![New Relic](https://img.shields.io/badge/New_Relic-1CE783?style=flat-square&logo=newrelic&logoColor=black) |
| **Systems & data** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |

<details>
<summary><b>📜 Certifications (9)</b></summary>

- AWS Certified Solutions Architect - Associate
- AWS Certified Cloud Practitioner
- Oracle Cloud Infrastructure 2025 Certified Foundations Associate
- OCI 2025 Certified AI Foundations Associate
- Microsoft Azure Fundamentals (AZ-900)
- SRE Foundation
- GitLab Certified Associate
- GitHub Foundations
- PCEP - Certified Entry-Level Python Programmer

</details>

<details>
<summary><b>💼 Experience</b></summary>

| Period | Company | Role |
|---|---|---|
| 2022 - now | UOL | DevOps Engineer / SRE |
| 2021 - 2022 | Accenture Brazil | DevOps / Automation Developer (Cloud & AIOps) |
| 2021 | NAVA Technology | DevOps Analyst |
| 2018 - 2021 | Locaweb | Support Analyst II / SysAdmin |
| 2015 - 2018 | CDF / Terra Networks | Support Analyst |

🎓 Associate degree in Internet Systems, Universidade Cruzeiro do Sul (2022)

</details>

## 🤝 Giving back

Cloud Computing mentor at **Escola da Nuvem**, helping people start their cloud careers with AWS fundamentals, certification prep and good practices.

---

<sub>`$ uptime` → still learning, still shipping. Always happy to talk SRE, Kubernetes and cloud.</sub>
