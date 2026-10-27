<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img alt="kubectl describe engineer lucas-pinheiro-alves: SRE / DevOps Engineer, Cloud & Platform. Status: Ready." src="./assets/banner-light.svg" width="100%">
</picture>

### Eu mantenho a produção entediante.

Engenheiro SRE / DevOps com mais de 10 anos em TI, 5+ deles em cloud. Cuido de infraestrutura de alta criticidade, onde cair não é opção. Construo observabilidade que alerta pelo motivo certo, automatizo o trabalho repetitivo e escrevo o post-mortem para o problema não voltar.

Meu foco atual é construir com IA: vibe coding, skills, integrações MCP e produtos SaaS, apoiado pela minha experiência em confiabilidade e automação.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-lucas--alvesp-0A66C2?style=flat-square)](https://www.linkedin.com/in/lucas-a-282a36371/)
![Aberto a vagas remotas](https://img.shields.io/badge/Aberto_a-remoto_SRE_%C2%B7_DevOps_%C2%B7_Platform-3fb950?style=flat-square)

🌎 [Read in English](./README.md)

## 📈 Resultados

| | |
|---|---|
| **5.000 servidores** migrados de CentOS para Oracle Linux | Playbooks Ansible reduziram a equipe de 10 pessoas para 2 e o prazo de 1 ano para 2 meses |
| **140 domínios** com SSL/TLS no piloto automático | Automação do ciclo de vida de certificados eliminou uma classe inteira de incidentes por expiração |
| **5.000+ servidores e serviços** observáveis | Dashboards, alertas acionáveis e SLOs de ponta a ponta |
| **Migração de plataforma CI/CD** | Repositórios e esteiras migrados com scripts de migração, validação e documentação |

## 🌱 Open source

**13 PRs mesclados** no [**habblaud**](https://github.com/marmottajr/habblaud) (⭐ 400+), um escritório virtual em TypeScript para agentes de IA. Cada um pequeno e focado, com teste de regressão ou medição de antes e depois.

- **CI e cadeia de suprimentos:** o primeiro workflow de CI do projeto no GitHub Actions ([#17](https://github.com/marmottajr/habblaud/pull/17)), Dependabot para npm, Docker e Actions ([#75](https://github.com/marmottajr/habblaud/pull/75)), imagem base presa pelo digest ([#93](https://github.com/marmottajr/habblaud/pull/93)) e o `/tmp` em memória do container limitado a 64 MB ([#94](https://github.com/marmottajr/habblaud/pull/94)).
- **Confiabilidade:** rotação de transcript quando o sistema reaproveita o inode ([#14](https://github.com/marmottajr/habblaud/pull/14)), arquivo reescrito no mesmo lugar ([#90](https://github.com/marmottajr/habblaud/pull/90)), empate na fila de permissões no mesmo milissegundo ([#88](https://github.com/marmottajr/habblaud/pull/88)) e o limite diário de esperas ([#89](https://github.com/marmottajr/habblaud/pull/89)).
- **Interface:** cartões de uso que não cobrem mais a barra ([#87](https://github.com/marmottajr/habblaud/pull/87)), correções da barra e do "Meu dia" no celular ([#91](https://github.com/marmottajr/habblaud/pull/91), [#92](https://github.com/marmottajr/habblaud/pull/92)), avisos acima da barra do timelapse ([#85](https://github.com/marmottajr/habblaud/pull/85)).
- **Documentação:** guia de contribuição em português ([#46](https://github.com/marmottajr/habblaud/pull/46)).

🔄 **Em revisão:** suporte ao OpenCode e ao Antigravity (eventos ao vivo, aprovações, mensagens, uso), dividido em 9 PRs empilhados ([#47](https://github.com/marmottajr/habblaud/pull/47), [#76–#83](https://github.com/marmottajr/habblaud/pulls?q=is%3Apr+is%3Aopen+author%3Alpalvess)), e a versão do app no título da janela no [tobi/disktree#83](https://github.com/tobi/disktree/pull/83).

## 🛠️ Projetos

- **Chronos** *(projeto pessoal)* — Widget para Windows que acompanha o uso do Claude Code em contas do Windows e WSL, desenvolvido com Rust, Tauri 2 e TypeScript.
- [**sourced-postmortem**](https://github.com/lpalvess/sourced-postmortem) — Verificador em Python que confere postmortems contra logs e métricas, valida timelines e ações e roda em Docker sem acesso à rede.
- [**sourced-carousel**](https://github.com/lpalvess/sourced-carousel) — Gera carrosséis em PDF/PNG com uma etapa de validação dos números dos slides contra os fatos fornecidos, em contêiner sem rede. *Plugin submetido à Anthropic; aguardando aprovação.*
- [**study-loop**](https://github.com/lpalvess/study-loop-skill) — Skill para assistentes de código com IA, com recuperação ativa, flashcards e repetição espaçada, usando armazenamento local em Python.

**Segurança e qualidade na prática:** atualização de dependências com Dependabot, imagens de contêiner fixadas por digest, execução sem rede e ocultação de credenciais; testes unitários e de regressão com Vitest, além de testes de ponta a ponta com Playwright.

## 🧰 Ferramentas

| | |
|---|---|
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square) ![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) |
| **Containers** | ![Kubernetes](https://img.shields.io/badge/Kubernetes_%28EKS,_OKE%29-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) |
| **Linguagens** | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white) |
| **Desktop e frontend** | ![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **IaC e automação** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) |
| **CI/CD** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) |
| **Engenharia com IA** | ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white) ![OpenAI Codex](https://img.shields.io/badge/OpenAI_Codex-412991?style=flat-square) ![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white) ![OpenCode](https://img.shields.io/badge/OpenCode-211E1E?style=flat-square) ![Antigravity](https://img.shields.io/badge/Antigravity-4285F4?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white) |
| **Testes e QA** | ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) |
| **Observabilidade** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square) ![ELK](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticsearch&logoColor=white) ![New Relic](https://img.shields.io/badge/New_Relic-1CE783?style=flat-square&logo=newrelic&logoColor=black) |
| **Sistemas e dados** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |

<details>
<summary><b>📜 Certificações (9)</b></summary>

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
<summary><b>💼 Experiência</b></summary>

| Período | Empresa | Função |
|---|---|---|
| 2022 - atual | UOL | DevOps Engineer / SRE |
| 2021 - 2022 | Accenture Brasil | DevOps / Automation Developer (Cloud e AIOps) |
| 2021 | NAVA Technology | Analista DevOps |
| 2018 - 2021 | Locaweb | Analista de Suporte II / SysAdmin |
| 2015 - 2018 | CDF / Terra Networks | Analista de Suporte |

🎓 Tecnólogo em Sistemas para Internet, Universidade Cruzeiro do Sul (2022)

</details>

## 🤝 Retribuindo

Mentor de Cloud Computing na **Escola da Nuvem**, ajudando quem está começando em cloud com fundamentos de AWS, preparação para certificações e boas práticas.

---

<sub>`$ uptime` → aprendendo e entregando. Sempre topo conversar sobre SRE, Kubernetes e cloud.</sub>
