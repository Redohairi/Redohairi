<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Davi%20Borges&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Software%20Engineer%20%7C%20Backend%20%26%20Data%20Engines&descAlignY=55&descSize=18" width="100%" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/davi-csb/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Redohairi)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daviborges07@gmail.com)

</div>

---

## 👨‍💻 Sobre mim

- ⚙️ Engenheiro de Software especializado em **backend, automação de processos (RPA) e pipelines de dados em escala**
- 🏛️ Experiência com sistemas críticos de alta disponibilidade em ambientes governamentais **(INSS/DTI)**
- 🧱 Apaixonado por **Clean Architecture, SOLID e TDD** aplicados a problemas reais de concorrência e integração
- 🌎 Based in Brasília, Brasil

---

## 🔭 Atualmente

| Status | Detalhe |
| :--- | :--- |
| 🚀 Trabalhando em | Plataforma de dados linguísticos multimodais para alinhamento de LLMs (RLHF/DPO) |
| 📚 Estudando | Sistemas Distribuídos, Data Engineering avançado e MLOps |
| 🎯 Objetivo | Contribuir com projetos open source de infra de dados e IA |

---

## 🚀 Projetos em Destaque

### 🌐 [Mebêngôkre Data Engine & API](https://github.com/Redohairi) *(Projeto IA/RLHF)*
> Plataforma backend distribuída para coleta e revisão de dados linguísticos multimodais (Áudio/Texto), projetada para alinhar LLMs via *Direct Preference Optimization* (Intel Gaudi).

- **Concorrência:** Orquestração de micro-tarefas com `SELECT FOR UPDATE SKIP LOCKED` no PostgreSQL — zero *race conditions* com dezenas de workers simultâneos
- **Resiliência:** Rotas idempotentes + NeonDB Serverless com pooling duplo (PgBouncer/Direct) para evitar *cold starts*
- **Dados:** Pipeline ETL incremental processando **+440k sentenças** com NLTK, deduplicação via SHA256
- ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)

---

### 🤖 [Automação de Monitoramento NOC](https://github.com/Redohairi)
> Sistema de *scraping* paralelo para monitoramento em tempo real de infraestruturas de rede críticas.

- **Escala:** Coleta simultânea em **+2.000 endpoints SOAP** com tolerância a falhas e *retries* automáticos
- **Engenharia:** Controle de *rate limit* e execução assíncrona para evitar bloqueios e gargalos
- ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Asyncio](https://img.shields.io/badge/Asyncio-3776AB?style=flat&logo=python&logoColor=white) ![BeautifulSoup4](https://img.shields.io/badge/BeautifulSoup4-59666C?style=flat&logo=python&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=flat&logo=playwright&logoColor=white)

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
![BeautifulSoup4](https://img.shields.io/badge/BeautifulSoup4-59666C?style=for-the-badge&logo=python&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-3776AB?style=for-the-badge&logo=python&logoColor=white)
![UiPath](https://img.shields.io/badge/UiPath-FA4616?style=for-the-badge&logo=uipath&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)

**QA & Boas Práticas**

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![TDD](https://img.shields.io/badge/TDD-Test%20Driven-brightgreen?style=for-the-badge)
![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-333333?style=for-the-badge)
![SOLID](https://img.shields.io/badge/SOLID-6DB33F?style=for-the-badge)

**Infra & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## 📈 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Redohairi&show_icons=true&theme=radical&hide_border=true" alt="Estatísticas do GitHub" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Redohairi&layout=compact&theme=radical&hide_border=true" alt="Linguagens Mais Usadas" width="48%" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Redohairi&theme=radical&hide_border=true" alt="GitHub Streak" width="60%" />
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%" />
</div>
