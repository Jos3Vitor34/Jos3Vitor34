<p align="right">
  <a href="./README.md">🇺🇸 English</a> ·
  <strong>🇧🇷 Português</strong>
</p>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,55:0B3D91,100:1F6FEB&height=200&section=header&text=Jos%C3%A9%20Vitor%20Ferreira&fontSize=44&fontColor=FFFFFF&fontAlignY=36&desc=Desenvolvedor%20Python%20Backend%20%C2%B7%20Google%20Cloud%20%C2%B7%20Automa%C3%A7%C3%A3o&descSize=18&descAlignY=58" alt="José Vitor Ferreira — Desenvolvedor Python Backend" />

<a href="https://github.com/Jos3Vitor34">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=900&color=1F6FEB&center=true&vCenter=true&width=620&lines=Criando+APIs+com+Python+%26+FastAPI;Publicando+apps+serverless+no+Google+Cloud;Automatizando+processos+de+ponta+a+ponta;Aberto+a+vagas+de+Dev+J%C3%BAnior" alt="Typing SVG" />
</a>

<br />

<a href="https://www.linkedin.com/in/jose-vitor-ferreira/"><img src="https://img.shields.io/badge/Aberto%20a-vagas%20de%20Dev%20J%C3%BAnior-2EA043?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Aberto a vagas de Dev Júnior" /></a>
<img src="https://img.shields.io/badge/Ponta%20Grossa%2C%20PR-Brasil-0B3D91?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Ponta Grossa, PR, Brasil" />

</div>

---

## 👨‍💻 Sobre Mim

Sou **desenvolvedor Python backend** e construo APIs, serviços em nuvem e automações que resolvem problemas reais de negócio. Atuei por **1,5 ano como Desenvolvedor Júnior** entregando automações de WhatsApp, integrações, otimizações de SQL e dashboards de KPIs para clientes, com resultados mensuráveis (até **+20% de conversão** e **mais de R$ 10 mil/mês em economia**).

Hoje meu foco é **engenharia backend em nível de produção no Google Cloud**: APIs assíncronas, pipelines de dados determinísticos, CI/CD, segurança e testes automatizados.

<table>
  <tr>
    <td>🔭 &nbsp;Desenvolvendo o <a href="https://github.com/Jos3Vitor34/quantis-cloud"><b>Quantis Cloud</b></a>, plataforma de auditoria financeira em Cloud Run + Vertex AI</td>
  </tr>
  <tr>
    <td>☁️ &nbsp;<b>5 credenciais verificadas</b>: 4 skill badges do Google Cloud + <i>Introduction to Cybersecurity</i> da Cisco</td>
  </tr>
  <tr>
    <td>🎓 &nbsp;Análise e Desenvolvimento de Sistemas na UNIASSELVI, com conclusão em <b>dezembro de 2026</b></td>
  </tr>
  <tr>
    <td>🧪 &nbsp;Valorizo <b>testes, arquitetura limpa, segurança e manutenibilidade</b></td>
  </tr>
  <tr>
    <td>💬 &nbsp;Português (nativo) · Inglês (leitura e escrita técnica avançada)</td>
  </tr>
</table>

---

## 🚀 Projeto em Destaque: Quantis Cloud

<div align="center">

<a href="https://quantis-web-1025217367368.us-central1.run.app/"><img src="https://img.shields.io/badge/▶%20Demo%20ao%20vivo-acesso%20em%201%20clique-1F6FEB?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Demo ao vivo" /></a>
<a href="https://github.com/Jos3Vitor34/quantis-cloud/blob/main/README.pt-BR.md"><img src="https://img.shields.io/badge/C%C3%B3digo--fonte-quantis--cloud-181717?style=for-the-badge&logo=github&logoColor=white" alt="Código-fonte" /></a>

<a href="https://github.com/Jos3Vitor34/quantis-cloud/actions/workflows/ci.yml"><img src="https://github.com/Jos3Vitor34/quantis-cloud/actions/workflows/ci.yml/badge.svg?branch=main" alt="CI" /></a>
<a href="https://github.com/Jos3Vitor34/quantis-cloud/actions/workflows/cd.yml"><img src="https://github.com/Jos3Vitor34/quantis-cloud/actions/workflows/cd.yml/badge.svg?branch=main" alt="CD" /></a>
<img src="https://img.shields.io/badge/testes-2.544%20passando-2EA043" alt="2.544 testes passando" />
<img src="https://img.shields.io/badge/licen%C3%A7a-Apache%202.0-blue" alt="Apache 2.0" />

</div>

> **Detecção determinística de anomalias financeiras com relatórios generativos protegidos, em Google Cloud com escala a zero.**

O Quantis Cloud audita planilhas financeiras (CSV / XLSX) e lotes de transações em busca das anomalias que um auditor procura primeiro: **duplicidades, outliers estatísticos, desvios da Lei de Benford, pagamentos fracionados abaixo do limite de aprovação e injeção de fórmulas em planilhas**. Ele segue uma regra: ***todo número é calculado, nunca gerado.*** Um motor em Python produz todos os valores, e o Vertex AI Gemini apenas redige a narrativa, que é rejeitada se citar algum número que o motor não calculou.

<table>
  <tr>
    <td width="50%"><a href="https://github.com/Jos3Vitor34/quantis-cloud"><img src="https://raw.githubusercontent.com/Jos3Vitor34/quantis-cloud/main/docs/screenshots/02-spreadsheet-audit.png" alt="Área de auditoria de planilhas" /></a></td>
    <td width="50%"><a href="https://github.com/Jos3Vitor34/quantis-cloud"><img src="https://raw.githubusercontent.com/Jos3Vitor34/quantis-cloud/main/docs/screenshots/04-benford-analysis.png" alt="Análise da Lei de Benford" /></a></td>
  </tr>
  <tr>
    <td align="center"><sub>Área de auditoria de planilhas</sub></td>
    <td align="center"><sub>Análise do primeiro dígito pela Lei de Benford</sub></td>
  </tr>
</table>

| | Destaque de engenharia |
| :---: | :--- |
| 🛡️ | **Numeric Consistency Guard**: cada número da narrativa da IA é conferido com os resultados determinísticos; um único valor não verificado faz o sistema voltar ao relatório do motor de regras |
| 🧮 | **Motor estatístico**: Lei de Benford (χ²), Tukey IQR, Z-score modificado, detecção de duplicidades e regras de fracionamento com pandas e NumPy |
| 🔐 | **Segurança**: neutralização de injeção de fórmulas CSV/Excel, Argon2id, JWTs de curta duração, refresh tokens rotativos e isolamento entre tenants |
| ☁️ | **GCP serverless**: Cloud Run (escala a zero), Cloud Tasks, Cloud Storage, Secret Manager e Vertex AI, projetado para custar **menos de US$ 10/mês** |
| 🔑 | **CD sem chaves**: GitHub Actions + Workload Identity Federation, migrations, revisões candidatas e smoke checks antes de liberar o tráfego |
| ✅ | **2.196 testes de backend + 348 de frontend** com PostgreSQL 16 real, mypy strict, Ruff, ESLint e especificação OpenAPI contract-first |

<p>
  <img src="https://img.shields.io/badge/Python%203.12-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/SQLAlchemy%202.0-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/PostgreSQL%2016-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/React%2018-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind%20v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Cloud%20Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Cloud Run" />
  <img src="https://img.shields.io/badge/Vertex%20AI%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Vertex AI" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

## 🏅 Certificações & Skill Badges

<p>Verificadas no <a href="https://www.credly.com/users/jose-vitor-ferreira"><b>Credly</b></a> e no <a href="https://www.linkedin.com/in/jose-vitor-ferreira/details/certifications/"><b>LinkedIn</b></a>. Clique em um emblema para verificá-lo.</p>

<table align="center">
  <tr>
    <td align="center" width="20%">
      <a href="https://www.credly.com/badges/eb4e0a71-07d2-491f-85f3-201d2576fcbe/public_url"><img src="https://images.credly.com/size/220x220/images/b18154fb-9bd3-47e5-a6f1-554be512947d/image.png" width="100" alt="Build Infrastructure with Terraform on Google Cloud" /></a><br />
      <sub><b>Build Infrastructure with Terraform on Google Cloud</b></sub><br />
      <sub>Google Cloud · nov 2026</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://www.credly.com/badges/263a377f-c27e-405b-9618-f7a2f617c523/public_url"><img src="https://images.credly.com/size/220x220/images/81d18a6f-00e5-42bf-83ca-c05f61b72f84/blob" width="100" alt="Implement Event-Driven Messaging and Automation Workflows" /></a><br />
      <sub><b>Implement Event-Driven Messaging and Automation Workflows</b></sub><br />
      <sub>Google Cloud · out 2026</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://www.credly.com/badges/9738fb71-d2e4-4df1-b4e6-ef92acbfb894/public_url"><img src="https://images.credly.com/size/220x220/images/b126c61c-4781-4f03-9b2b-062963003abf/image.png" width="100" alt="Develop Your Google Cloud Network" /></a><br />
      <sub><b>Develop Your Google Cloud Network</b></sub><br />
      <sub>Google Cloud · out 2026</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://www.credly.com/badges/508bcfea-1351-4fcc-a7db-c1fbc7cba1dc/public_url"><img src="https://images.credly.com/size/220x220/images/eea11cba-2a98-4bbe-bad2-447878dd34a2/image.png" width="100" alt="Implement Load Balancing on Compute Engine" /></a><br />
      <sub><b>Implement Load Balancing on Compute Engine</b></sub><br />
      <sub>Google Cloud · out 2026</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://www.credly.com/badges/bc6f5fbd-ed31-46c8-bc43-52beb49eb09b/public_url"><img src="https://images.credly.com/size/220x220/images/af8c6b4e-fc31-47c4-8dcb-eb7a2065dc5b/I2CS__1_.png" width="100" alt="Introduction to Cybersecurity" /></a><br />
      <sub><b>Introduction to Cybersecurity</b></sub><br />
      <sub>Cisco · out 2026</sub>
    </td>
  </tr>
</table>

---

## 🛠️ Habilidades & Tecnologias

### Backend & Python

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/Alembic-6BAA3D?style=for-the-badge&logo=python&logoColor=white" alt="Alembic" />
  <img src="https://img.shields.io/badge/REST%20APIs-02569B?style=for-the-badge&logo=openapiinitiative&logoColor=white" alt="REST APIs" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />
</p>

### Cloud & Infraestrutura

<p align="left">
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/Cloud%20Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Cloud Run" />
  <img src="https://img.shields.io/badge/Vertex%20AI-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Vertex AI" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

### Bancos de Dados & Processamento Assíncrono

<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" alt="Celery" />
</p>

### Frontend

<p align="left">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" alt="TanStack Query" />
</p>

### Integrações, Automação & IA

<p align="left">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white" alt="Make" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSJ3aGl0ZSIgcm9sZT0iaW1nIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BPHRpdGxlPk9wZW5BSTwvdGl0bGU%2BPHBhdGggZD0iTTIyLjI4MTkgOS44MjExYTUuOTg0NyA1Ljk4NDcgMCAwIDAtLjUxNTctNC45MTA4IDYuMDQ2MiA2LjA0NjIgMCAwIDAtNi41MDk4LTIuOUE2LjA2NTEgNi4wNjUxIDAgMCAwIDQuOTgwNyA0LjE4MThhNS45ODQ3IDUuOTg0NyAwIDAgMC0zLjk5NzcgMi45IDYuMDQ2MiA2LjA0NjIgMCAwIDAgLjc0MjcgNy4wOTY2IDUuOTggNS45OCAwIDAgMCAuNTExIDQuOTEwNyA2LjA1MSA2LjA1MSAwIDAgMCA2LjUxNDYgMi45MDAxQTUuOTg0NyA1Ljk4NDcgMCAwIDAgMTMuMjU5OSAyNGE2LjA1NTcgNi4wNTU3IDAgMCAwIDUuNzcxOC00LjIwNTggNS45ODk0IDUuOTg5NCAwIDAgMCAzLjk5NzctMi45MDAxIDYuMDU1NyA2LjA1NTcgMCAwIDAtLjc0NzUtNy4wNzI5em0tOS4wMjIgMTIuNjA4MWE0LjQ3NTUgNC40NzU1IDAgMCAxLTIuODc2NC0xLjA0MDhsLjE0MTktLjA4MDQgNC43NzgzLTIuNzU4MmEuNzk0OC43OTQ4IDAgMCAwIC4zOTI3LS42ODEzdi02LjczNjlsMi4wMiAxLjE2ODZhLjA3MS4wNzEgMCAwIDEgLjAzOC4wNTJ2NS41ODI2YTQuNTA0IDQuNTA0IDAgMCAxLTQuNDk0NSA0LjQ5NDR6bS05LjY2MDctNC4xMjU0YTQuNDcwOCA0LjQ3MDggMCAwIDEtLjUzNDYtMy4wMTM3bC4xNDIuMDg1MiA0Ljc4MyAyLjc1ODJhLjc3MTIuNzcxMiAwIDAgMCAuNzgwNiAwbDUuODQyOC0zLjM2ODV2Mi4zMzI0YS4wODA0LjA4MDQgMCAwIDEtLjAzMzIuMDYxNUw5Ljc0IDE5Ljk1MDJhNC40OTkyIDQuNDk5MiAwIDAgMS02LjE0MDgtMS42NDY0ek0yLjM0MDggNy44OTU2YTQuNDg1IDQuNDg1IDAgMCAxIDIuMzY1NS0xLjk3MjhWMTEuNmEuNzY2NC43NjY0IDAgMCAwIC4zODc5LjY3NjVsNS44MTQ0IDMuMzU0My0yLjAyMDEgMS4xNjg1YS4wNzU3LjA3NTcgMCAwIDEtLjA3MSAwbC00LjgzMDMtMi43ODY1QTQuNTA0IDQuNTA0IDAgMCAxIDIuMzQwOCA3Ljg3MnptMTYuNTk2MyAzLjg1NThMMTMuMTAzOCA4LjM2NCAxNS4xMTkyIDcuMmEuMDc1Ny4wNzU3IDAgMCAxIC4wNzEgMGw0LjgzMDMgMi43OTEzYTQuNDk0NCA0LjQ5NDQgMCAwIDEtLjY3NjUgOC4xMDQydi01LjY3NzJhLjc5Ljc5IDAgMCAwLS40MDctLjY2N3ptMi4wMTA3LTMuMDIzMWwtLjE0Mi0uMDg1Mi00Ljc3MzUtMi43ODE4YS43NzU5Ljc3NTkgMCAwIDAtLjc4NTQgMEw5LjQwOSA5LjIyOTdWNi44OTc0YS4wNjYyLjA2NjIgMCAwIDEgLjAyODQtLjA2MTVsNC44MzAzLTIuNzg2NmE0LjQ5OTIgNC40OTkyIDAgMCAxIDYuNjgwMiA0LjY2ek04LjMwNjUgMTIuODYzbC0yLjAyLTEuMTYzOGEuMDgwNC4wODA0IDAgMCAxLS4wMzgtLjA1NjdWNi4wNzQyYTQuNDk5MiA0LjQ5OTIgMCAwIDEgNy4zNzU3LTMuNDUzN2wtLjE0Mi4wODA1TDguNzA0IDUuNDU5YS43OTQ4Ljc5NDggMCAwIDAtLjM5MjcuNjgxM3ptMS4wOTc2LTIuMzY1NGwyLjYwMi0xLjQ5OTggMi42MDY5IDEuNDk5OHYyLjk5OTRsLTIuNTk3NCAxLjQ5OTctMi42MDY3LTEuNDk5N1oiLz48L3N2Zz4%3D" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/WhatsApp%20API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp API" />
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" alt="Stripe" />
</p>

### Testes & Qualidade de Código

<p align="left">
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest" />
  <img src="https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black" alt="Ruff" />
  <img src="https://img.shields.io/badge/mypy-2A6DB2?style=for-the-badge&logo=python&logoColor=white" alt="mypy" />
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint" />
</p>

### Dados & BI

<p align="left">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSJibGFjayIgcm9sZT0iaW1nIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BPHRpdGxlPlBvd2VyIEJJPC90aXRsZT48cGF0aCBkPSJNMTAgMTJhMSAxIDAgMCAxIDEgMXYxMUg0YTEgMSAwIDAgMS0xLTFWMTNhMSAxIDAgMCAxIDEtMWg2Wm0tMi0uNVY3YTEgMSAwIDAgMSAxLTFoNmExIDEgMCAwIDEgMSAxdjE3aC00LjVWMTNhMS41IDEuNSAwIDAgMC0xLjUtMS41SDhabTUtNlYxYTEgMSAwIDAgMSAxLTFoNmExIDEgMCAwIDEgMSAxdjIyYTEgMSAwIDAgMS0xIDFoLTMuNVY3QTEuNSAxLjUgMCAwIDAgMTUgNS41aC0yWiIvPjwvc3ZnPg%3D%3D" alt="Power BI" />
  <img src="https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white" alt="Looker Studio" />
</p>

---

## 💼 Experiência Profissional

<table>
  <tr>
    <td>
      <h3>Desenvolvedor Júnior · ESC Automações Digitais Ltda.</h3>
      <sub>📅 Junho de 2024 – Janeiro de 2026</sub>
      <br /><br />
      <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" />
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSJ3aGl0ZSIgcm9sZT0iaW1nIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BPHRpdGxlPk9wZW5BSTwvdGl0bGU%2BPHBhdGggZD0iTTIyLjI4MTkgOS44MjExYTUuOTg0NyA1Ljk4NDcgMCAwIDAtLjUxNTctNC45MTA4IDYuMDQ2MiA2LjA0NjIgMCAwIDAtNi41MDk4LTIuOUE2LjA2NTEgNi4wNjUxIDAgMCAwIDQuOTgwNyA0LjE4MThhNS45ODQ3IDUuOTg0NyAwIDAgMC0zLjk5NzcgMi45IDYuMDQ2MiA2LjA0NjIgMCAwIDAgLjc0MjcgNy4wOTY2IDUuOTggNS45OCAwIDAgMCAuNTExIDQuOTEwNyA2LjA1MSA2LjA1MSAwIDAgMCA2LjUxNDYgMi45MDAxQTUuOTg0NyA1Ljk4NDcgMCAwIDAgMTMuMjU5OSAyNGE2LjA1NTcgNi4wNTU3IDAgMCAwIDUuNzcxOC00LjIwNTggNS45ODk0IDUuOTg5NCAwIDAgMCAzLjk5NzctMi45MDAxIDYuMDU1NyA2LjA1NTcgMCAwIDAtLjc0NzUtNy4wNzI5em0tOS4wMjIgMTIuNjA4MWE0LjQ3NTUgNC40NzU1IDAgMCAxLTIuODc2NC0xLjA0MDhsLjE0MTktLjA4MDQgNC43NzgzLTIuNzU4MmEuNzk0OC43OTQ4IDAgMCAwIC4zOTI3LS42ODEzdi02LjczNjlsMi4wMiAxLjE2ODZhLjA3MS4wNzEgMCAwIDEgLjAzOC4wNTJ2NS41ODI2YTQuNTA0IDQuNTA0IDAgMCAxLTQuNDk0NSA0LjQ5NDR6bS05LjY2MDctNC4xMjU0YTQuNDcwOCA0LjQ3MDggMCAwIDEtLjUzNDYtMy4wMTM3bC4xNDIuMDg1MiA0Ljc4MyAyLjc1ODJhLjc3MTIuNzcxMiAwIDAgMCAuNzgwNiAwbDUuODQyOC0zLjM2ODV2Mi4zMzI0YS4wODA0LjA4MDQgMCAwIDEtLjAzMzIuMDYxNUw5Ljc0IDE5Ljk1MDJhNC40OTkyIDQuNDk5MiAwIDAgMS02LjE0MDgtMS42NDY0ek0yLjM0MDggNy44OTU2YTQuNDg1IDQuNDg1IDAgMCAxIDIuMzY1NS0xLjk3MjhWMTEuNmEuNzY2NC43NjY0IDAgMCAwIC4zODc5LjY3NjVsNS44MTQ0IDMuMzU0My0yLjAyMDEgMS4xNjg1YS4wNzU3LjA3NTcgMCAwIDEtLjA3MSAwbC00LjgzMDMtMi43ODY1QTQuNTA0IDQuNTA0IDAgMCAxIDIuMzQwOCA3Ljg3MnptMTYuNTk2MyAzLjg1NThMMTMuMTAzOCA4LjM2NCAxNS4xMTkyIDcuMmEuMDc1Ny4wNzU3IDAgMCAxIC4wNzEgMGw0LjgzMDMgMi43OTEzYTQuNDk0NCA0LjQ5NDQgMCAwIDEtLjY3NjUgOC4xMDQydi01LjY3NzJhLjc5Ljc5IDAgMCAwLS40MDctLjY2N3ptMi4wMTA3LTMuMDIzMWwtLjE0Mi0uMDg1Mi00Ljc3MzUtMi43ODE4YS43NzU5Ljc3NTkgMCAwIDAtLjc4NTQgMEw5LjQwOSA5LjIyOTdWNi44OTc0YS4wNjYyLjA2NjIgMCAwIDEgLjAyODQtLjA2MTVsNC44MzAzLTIuNzg2NmE0LjQ5OTIgNC40OTkyIDAgMCAxIDYuNjgwMiA0LjY2ek04LjMwNjUgMTIuODYzbC0yLjAyLTEuMTYzOGEuMDgwNC4wODA0IDAgMCAxLS4wMzgtLjA1NjdWNi4wNzQyYTQuNDk5MiA0LjQ5OTIgMCAwIDEgNy4zNzU3LTMuNDUzN2wtLjE0Mi4wODA1TDguNzA0IDUuNDU5YS43OTQ4Ljc5NDggMCAwIDAtLjM5MjcuNjgxM3ptMS4wOTc2LTIuMzY1NGwyLjYwMi0xLjQ5OTggMi42MDY5IDEuNDk5OHYyLjk5OTRsLTIuNTk3NCAxLjQ5OTctMi42MDY3LTEuNDk5N1oiLz48L3N2Zz4%3D" alt="OpenAI" />
      <img src="https://img.shields.io/badge/REST%20APIs-02569B?style=flat-square" alt="REST APIs" />
      <img src="https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
      <img src="https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white" alt="Looker Studio" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
    </td>
  </tr>
</table>

| Impacto | O que eu fiz |
| :---: | :--- |
| **+20%** de conversão de lead em venda | Criei fluxos de automação para WhatsApp com **n8n, APIs REST e modelos da OpenAI**, agilizando o tempo de resposta aos clientes |
| **+R$ 10 mil/mês** economizados pelos clientes | Estruturei um processo de criação e aprovação de templates de mensagens da API do WhatsApp na categoria **Utilidade**, reduzindo custos de envio |
| **+15%** de conversão de leads | Integrei sistemas externos via **APIs REST e processamento de JSON** e desenvolvi landing pages otimizadas |
| **~30%** mais desempenho em relatórios | Melhorei a modelagem do banco de dados e otimizei **consultas SQL** complexas |
| **~20 h/semana** economizadas | Substituí planilhas manuais por dashboards em tempo real no **Looker Studio** para acompanhamento de custos e KPIs |

---

## 📂 Outros Projetos Públicos

| Projeto | Descrição | Stack |
| :--- | :--- | :--- |
| [**fastapi-vagas-emprego**](https://github.com/Jos3Vitor34/fastapi-vagas-emprego) | API RESTful para gestão de vagas, empresas e candidatos, com autenticação JWT e controle de permissões | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) |
| [**auto-relatorios-python**](https://github.com/Jos3Vitor34/auto-relatorios-python) | Ferramenta CLI que valida, agrupa e consolida várias planilhas de Excel em relatórios sumarizados | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white) |

---

## 🎓 Formação & 🌎 Idiomas

<table>
  <tr>
    <td width="55%" valign="top">
      <b>Tecnólogo em Análise e Desenvolvimento de Sistemas</b><br />
      Centro Universitário Leonardo da Vinci (UNIASSELVI)<br />
      <sub>📅 Fevereiro de 2023 – Dezembro de 2026 · Em andamento</sub>
    </td>
    <td width="45%" valign="top">
      🇧🇷 <b>Português</b>: Nativo<br />
      🇺🇸 <b>Inglês</b>: Leitura técnica avançada e escrita de documentação e relatórios técnicos
    </td>
  </tr>
</table>

---

## 📊 Atividade no GitHub

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Jos3Vitor34&theme=github-dark-blue&hide_border=true&border_radius=10&locale=pt_BR" alt="Sequência de contribuições no GitHub" />
  <br /><br />
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Jos3Vitor34&theme=github-compact&hide_border=true&area=true&radius=10" alt="Gráfico de contribuições" />
</div>

---

## 📫 Vamos Conversar

<p>Estou buscando ativamente <b>oportunidades como Desenvolvedor Júnior</b> (backend, Python, cloud ou automação). Fique à vontade para entrar em contato!</p>

<p align="left">
  <a href="https://www.linkedin.com/in/jose-vitor-ferreira/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSJ3aGl0ZSIgcm9sZT0iaW1nIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BPHRpdGxlPkxpbmtlZEluPC90aXRsZT48cGF0aCBkPSJNMjAuNDQ3IDIwLjQ1MmgtMy41NTR2LTUuNTY5YzAtMS4zMjgtLjAyNy0zLjAzNy0xLjg1Mi0zLjAzNy0xLjg1MyAwLTIuMTM2IDEuNDQ1LTIuMTM2IDIuOTM5djUuNjY3SDkuMzUxVjloMy40MTR2MS41NjFoLjA0NmMuNDc3LS45IDEuNjM3LTEuODUgMy4zNy0xLjg1IDMuNjAxIDAgNC4yNjcgMi4zNyA0LjI2NyA1LjQ1NXY2LjI4NnpNNS4zMzcgNy40MzNjLTEuMTQ0IDAtMi4wNjMtLjkyNi0yLjA2My0yLjA2NSAwLTEuMTM4LjkyLTIuMDYzIDIuMDYzLTIuMDYzIDEuMTQgMCAyLjA2NC45MjUgMi4wNjQgMi4wNjMgMCAxLjEzOS0uOTI1IDIuMDY1LTIuMDY0IDIuMDY1em0xLjc4MiAxMy4wMTlIMy41NTVWOWgzLjU2NHYxMS40NTJ6TTIyLjIyNSAwSDEuNzcxQy43OTIgMCAwIC43NzQgMCAxLjcyOXYyMC41NDJDMCAyMy4yMjcuNzkyIDI0IDEuNzcxIDI0aDIwLjQ1MUMyMy4yIDI0IDI0IDIzLjIyNyAyNCAyMi4yNzFWMS43MjlDMjQgLjc3NCAyMy4yIDAgMjIuMjIyIDBoLjAwM3oiLz48L3N2Zz4%3D" alt="LinkedIn" /></a>
  <a href="mailto:josevitorferreir@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://www.credly.com/users/jose-vitor-ferreira"><img src="https://img.shields.io/badge/Credly-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly" /></a>
  <a href="https://wa.me/5542998110948"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
  <a href="https://discord.com/users/799368091636072538"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,45:0B3D91,100:0D1117&height=110&section=footer" alt="" />
