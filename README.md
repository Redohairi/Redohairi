<div align="center">

<svg width="800" height="160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#161b22;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0d1117;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="800" height="160" fill="url(#grad)" rx="10"/>
  <text x="400" y="75" font-family="monospace" font-size="32" font-weight="bold" fill="white" text-anchor="middle">Davi Borges</text>
  <text x="400" y="110" font-family="monospace" font-size="15" fill="#58a6ff" text-anchor="middle">Software Engineer · Backend &amp; Data Engines · Python &amp; TypeScript</text>
</svg>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/davi-csb/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Redohairi)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daviborges07@gmail.com)

</div>

---

## 👨‍💻 Sobre mim

- ⚙️ Engenheiro de Software especializado em **backend, automação de processos (RPA) e pipelines de dados em escala**
- 🏛️ Experiência com sistemas críticos de alta disponibilidade em ambientes governamentais **(INSS/DTI)** — monitoramento de infraestrutura, detecção de incidentes e automação de processos operacionais
- 🎓 Graduando em **Computação — Licenciatura pela Universidade de Brasília (UnB)**
- 🔬 Futuro pesquisador com interesse em **IA, sistemas distribuídos e engenharia de dados**
- 🧱 Apaixonado por **Clean Architecture, SOLID e TDD** aplicados a problemas reais de concorrência e integração
- 🌎 Brasília, Brasil

---

## 🔭 Atualmente

| Status | Detalhe |
| :--- | :--- |
| 🚀 Trabalhando em | Plataforma de dados linguísticos multimodais para alinhamento de LLMs (RLHF/DPO) |
| 🎓 Cursando | Computação Licenciatura — UnB |
| 📚 Estudando | Sistemas Distribuídos, Data Engineering avançado e MLOps |
| 🔬 Objetivo | Pesquisa aplicada em IA, NLP e alinhamento de modelos de linguagem |

---

## 🚀 Projetos em Destaque

### 🌐 [Mebêngôkre Data Engine & API](https://github.com/Redohairi) *(Projeto IA/RLHF)*
> Plataforma backend distribuída para coleta e revisão de dados linguísticos multimodais (Áudio/Texto), projetada para alinhar LLMs via *Direct Preference Optimization* (Intel Gaudi).

- **Concorrência:** Orquestração de micro-tarefas com `SELECT FOR UPDATE SKIP LOCKED` no PostgreSQL — zero *race conditions* com dezenas de workers simultâneos
- **Resiliência:** Rotas idempotentes + NeonDB Serverless com pooling duplo (PgBouncer/Direct) para evitar *cold starts*
- **Dados:** Pipeline ETL incremental processando **+440k sentenças** com NLTK, deduplicação via SHA256
- ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)

---

### 🤖 [Plataforma de Monitoramento de Infraestrutura — INSS/DTI](https://github.com/Redohairi)
> Sistema de observabilidade e detecção de incidentes para monitoramento em tempo real de agências e circuitos de rede do INSS, integrado ao Zabbix.

- **Telemetria distribuída:** Pipeline de coleta paralela consultando **+2.200 endpoints SOAP** via `multithreading`, com parsing automático de respostas XML/HTML
- **Correlação de eventos:** Lógica para detecção automática de início e fim de incidentes operacionais a partir de análise de estados (`from_state` / `to_state`)
- **ETL leve:** Ingestão → transformação → exportação de datasets estruturados (CSV) com campos como `data_Hora_Inicio`, `Evento_Inicio`, `Evento_Fim`, `ID APS`, `Nome da APS`
- **Automação de tickets:** Integração com **Redmine** para atualização automática de issues a partir dos dados coletados, incluindo campos como Designação Telebrás
- **Automação web:** Scripts com **Selenium** para interação com sistemas legados internos — login, navegação e extração de dados
- **Arquitetura:** Evolução do projeto para padrão MVC com separação de entidades e utilitários reutilizáveis
- ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=flat&logo=zabbix&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white) ![Redmine](https://img.shields.io/badge/Redmine-B32024?style=flat&logo=redmine&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

### 🔄 [API de Enriquecimento e Normalização de Dados](https://github.com/Redohairi)
> Gateway de integração que atua como hub central para múltiplas fontes de dados externas.

- **Impacto:** Redução de inconsistências nos dados internos via validação estrita de contratos
- **Engenharia:** Integração com APIs de terceiros, serialização e normalização de *payloads* complexos com Pydantic
- ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)

---

## 🧰 Toolbox

**Backend & APIs**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Banco de Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![MongoDB Atlas](https://img.shields.io/badge/Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Automação & Scraping**

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=for-the-badge&logo=playwright&logoColor=white)
![BeautifulSoup4](https://img.shields.io/badge/BeautifulSoup4-59666C?style=for-the-goColor=white)
![Requests](https://img.shields.io/badge/Requests-3776AB?style=for-the-badge&logo=python&logoColor=white)
![UiPath](https://img.shields.io/badge/UiPath-FA4616?style=for-the-badge&logo=uipath&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)

**Observabilidade & Infra**

![Zabbix](https://img.shields.io/badge/Zabbix-CC0000?style=for-the-badge&logo=zabbix&logoColor=white)
![Redmine](https://img.shields.io/badge/Redmine-B32024?style=for-the-badge&logo=redmine&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**QA & Boas Práticas**

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![TDD](https://img.shields.io/badge/TDD-Test%20Driven-brightgreen?style=for-the-badge)
![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-333333?style=for-the-badge)
![SOLID](https://img.shields.io/badge/SOLID-6DB33F?style=for-the-badge)

---

## 📈 GitHub Analytics

<div align="center">
  <img src="github-metrics.svg" alt="GitHub Metrics" width="100%" />
</div>

---

<div align="center">
  <sub>Feito com ☕ e muitas linhas de código · UnB · Brasília</sub>
</div>
