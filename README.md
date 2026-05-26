<div align="center">

<svg width="800" height="150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0A0E17;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#161B22;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0A0E17;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="800" height="150" fill="url(#grad)" rx="8"/>
  <text x="400" y="70" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-size="32" font-weight="800" fill="#FFFFFF" text-anchor="middle" letter-spacing="1">Davi Borges</text>
  <text x="400" y="105" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif" font-size="15" fill="#58A6FF" text-anchor="middle" font-weight="500" letter-spacing="0.5">Software Engineer · Backend Architecture & Data Pipelines</text>
</svg>

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/davi-csb/)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daviborges07@gmail.com)

</div>

---

## 👨‍💻 Perfil Profissional

Engenheiro de Software com sólida base acadêmica pela **Universidade de Brasília (UnB)** e mais de 3 anos de experiência prática no desenvolvimento e sustentação de sistemas críticos. Especialista em arquitetura backend, automação de processos (RPA) e orquestração de dados em ambientes de alta disponibilidade.

- **Experiência Enterprise:** 2 anos de atuação no ecossistema governamental (**INSS/DTI**), projetando ferramentas operacionais e pipelines de automação para monitoramento e integração corporativa.
- **Pesquisa & Inovação (IA/NLP):** Desenvolvedor principal de soluções voltadas para preservação linguística de povos originários (projeto Kayapó/Mebêngôkre) e construção de data engines para alinhamento de LLMs.
- **Desenvolvimento Full-Cycle:** Experiência atuando diretamente com clientes corporativos na entrega de plataformas web responsivas (React) integradas a backends robustos (FastAPI/Python).
- **Engenharia de Qualidade:** Aplicação rigorosa de **Clean Architecture, SOLID e TDD** para resolver problemas complexos de concorrência e resiliência em sistemas distribuídos.
- 📍 Cidade Ocidental - GO.

---

## 🔭 Panorama Atual

| Foco | Descrição |
| :--- | :--- |
| **🚀 Construindo** | Plataforma de dados linguísticos multimodais para alinhamento de LLMs (RLHF/DPO) |
| **🎓 Formação** | Licenciatura em Computação / Ciência da Computação — UnB |
| **📚 Especialização** | Sistemas Distribuídos, Data Engineering avançado e MLOps |
| **🎯 Objetivos** | Pesquisa aplicada em IA, NLP e arquitetura de modelos de linguagem |

---

## 🚀 Projetos em Destaque

### 🌐 [Mebêngôkre Data Engine & API (mbg_pt)](https://github.com/Redohairi/mbg_pt) *(Projeto de Preservação Linguística & IA/RLHF)*
> Plataforma backend corporativa e distribuída projetada para a preservação do idioma indígena Kayapó (Mebêngôkre). O sistema atua na orquestração, revisão e validação de dados multimodais (Áudio/Texto) para alinhar LLMs via *Direct Preference Optimization* (DPO) utilizando aceleradores Intel Gaudi.

- **Pipelines de Exportação & ML:** Arquitetura orientada a dados com fluxos de ETL customizados para treinamento de modelos de IA, integrando submódulos específicos para exportação de dados voltados a **ASR** *(Speech Recognition)*, **TTS** *(Text-to-Speech)*, **SFT** e **DPO**.
- **Motor de Validação (Eligibility Engine):** Implementação de uma camada de validação robusta utilizando validadores linguísticos e simbólicos que garantem a governança, consistência estrutural e a integridade dos dados coletados.
- **Concorrência Otimizada & Resiliência:** Orquestração segura de micro-tarefas com `SELECT FOR UPDATE SKIP LOCKED` no PostgreSQL, garantindo zero *race conditions* com múltiplos workers simultâneos. Serviços arquitetados com foco em idempotência.
- **Qualidade & Segurança (TDD e RBAC):** Cobertura extensiva de testes validando transições de estado, concorrência, limites de taxa (*rate limiting*) e um sistema estrito de controle de acesso baseado em papéis (RBAC) para gerenciar fluxos de revisão e dead letters.

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy" />
</p>

### 🤖 [Plataforma de Monitoramento e Automação Operacional — INSS/DTI](https://github.com/Redohairi)
> Ecossistema interno de observabilidade, automação de incidentes e integração corporativa entre sistemas legados, utilizado no monitoramento de infraestrutura crítica e circuitos de conectividade do ambiente governamental.

- **Coleta Distribuída & Telemetria:** Implementação de pipelines de dados concorrentes via `multithreading` para consulta paralela de **+2.200 endpoints SOAP/XML**, reduzindo drasticamente a latência de diagnóstico e acompanhando em tempo real a disponibilidade de agências distribuídas nacionalmente.
- **Integração com Sistemas Legados & ETL:** Construção de rotinas integradas ao Zabbix e Monitor.INSS, atuando na ingestão, normalização (CSV/Excel) e consumo de APIs REST/SOAP com parsing avançado de XML e HTML.
- **Automação ITSM & Integração Ruby on Rails:** Desenvolvimento de mecanismos de correlação de incidentes baseados em transições de estado (`from_state` / `to_state`). Essa lógica orquestrava a atualização automatizada de chamados operacionais no **Redmine**, envolvendo integração direta com aplicações baseadas em **Ruby on Rails**.
- **RPA Corporativo:** Pipeline de automação web via **Selenium** para autenticação, navegação dinâmica e extração de dados em plataformas restritas, eliminando atividades manuais repetitivas e acelerando o troubleshooting na operação N1/N2.

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=flat-square&logo=ruby-on-rails&logoColor=white" alt="Ruby on Rails" />
  <img src="https://img.shields.io/badge/Zabbix-CC0000?style=flat-square&logo=zabbix&logoColor=white" alt="Zabbix" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" alt="Selenium" />
  <img src="https://img.shields.io/badge/Redmine-B32024?style=flat-square&logo=redmine&logoColor=white" alt="Redmine" />
</p>


## 🧰 Stack Tecnológico

<details open>
<summary><b>Backend & APIs</b></summary>
<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
</details>

<details open>
<summary><b>Frontend & UI</b></summary>
<br>

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
</details>

<details open>
<summary><b>Banco de Dados & Dados</b></summary>
<br>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
</details>

<details open>
<summary><b>Automação, Infra & QA</b></summary>
<br>

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=for-the-badge&logo=playwright&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-333333?style=for-the-badge)
![SOLID](https://img.shields.io/badge/SOLID-6DB33F?style=for-the-badge)
</details>

---

## 📈 Métricas do GitHub

<div align="center">
  <img src="github-metrics.svg" alt="GitHub Metrics" width="100%" />
</div>

<br>

<div align="center">
  <sub>Construído com ☕, arquitetura limpa e muita dedicação · <b>UnB — Brasília, Brasil</b></sub>
</div>
