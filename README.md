<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=30&duration=3000&pause=1200&color=58A6FF&center=true&vCenter=true&multiline=true&width=620&height=80&lines=Mateus+Munaro+%E2%80%94+Data+%26+Software+Engineer" alt="Typing SVG" />
</div>

<p align="center">
  <em>Arquitetando pipelines de dados, data warehouses e aplicações full-stack na <strong>Faz Capital</strong></em>
</p>

<p align="center">
  <a href="https://linkedin.com/in/SEU-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:seu-email@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://fazcapital.com.br"><img src="https://img.shields.io/badge/Faz_Capital-1a1a2e?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiI+PHRleHQgeD0iMCIgeT0iMTIiIGZvbnQtc2l6ZT0iMTIiPvCfj6Y8L3RleHQ+PC9zdmc+&logoColor=white"/></a>
</p>

---

### 🧑‍💻 Sobre

Engenheiro de dados e desenvolvedor full-stack com foco em **arquitetura de dados**, **pipelines ETL/ELT** e **BI analítico**. Atuo na **Faz Capital** projetando e mantendo toda a infraestrutura de dados — do ingest de leads multicanal até dashboards executivos de funil de conversão e gestão de portfólios offshore.

Também pesquisador acadêmico em **Gerência de Configuração de Software**, com artigo apresentado sobre ferramentas de merge e resolução de conflitos.

---

### ⚙️ O que eu construo no dia-a-dia

```
📊 Data Engineering          → Pipelines Airflow, modelagem dimensional, materialized views
🏗️ Data Warehouse            → Star schemas PostgreSQL, staging → facts/dims, ETL modular
📈 BI & Analytics            → Metabase dashboards, funnel analysis, Sankey charts, geo heatmaps
🔄 Automação & Orquestração  → n8n workflows, Airflow DAGs, triggers/procedures PostgreSQL
🌐 Full-Stack Apps           → Next.js + TypeScript frontend, FastAPI backend, Azure AD auth
📄 Relatórios & Scraping     → PDF generation (WeasyPrint), web scraping, factory patterns
```

---

### 🛠 Tech Stack

<div align="center">

| Data & Backend | Frontend | Infra & Ferramentas |
|:---:|:---:|:---:|
| <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" title="PostgreSQL"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" title="Python"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" title="FastAPI"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apacheairflow/apacheairflow-original.svg" title="Airflow"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" title="Redis"/> | <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" title="Next.js"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" title="React"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" title="TypeScript"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" title="HTML5"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" title="CSS3"/> | <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" title="Docker"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" title="Git"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" title="Linux"/> <img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" title="Azure"/> |
| PostgreSQL · Python · FastAPI · Airflow · Redis · n8n | Next.js · React · TypeScript · Three.js | Docker · Git · Linux/WSL · Azure AD · Metabase |

</div>

---

### 🏗️ Projetos em destaque

<table>
  <tr>
    <td width="50%">
      <h4>📊 Data Platform — Faz Capital</h4>
      <p>Plataforma completa de dados para assessoria de investimentos: ingestão multicanal de leads (Meta Ads, Google, orgânico), pipeline Airflow com dedup por <code>business_key_hash</code>, modelo dimensional (<code>dim_lead_unified</code>, <code>fct_lead_events</code>), materialized views de funil (<code>mv_funnel_base</code>) e dashboards Metabase com drill-down, Sankey e heatmaps geográficos.</p>
      <p><sub>PostgreSQL · Airflow · Metabase · n8n · Python</sub></p>
    </td>
    <td width="50%">
      <h4>💼 Portfolio Manager — Faz Consulting</h4>
      <p>Data warehouse e aplicação web para gestão de portfólios offshore (Investors Trust). Star schema com <code>dim_clients</code>, <code>dim_policy</code>, <code>dim_asset</code>, <code>fct_policy_positions</code>. ETL modular com orquestrador PostgreSQL, geração de relatórios PDF (WeasyPrint + Matplotlib), scraping de plataformas e autenticação Azure AD.</p>
      <p><sub>FastAPI · Next.js · TypeScript · PostgreSQL · WeasyPrint</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4>🔬 Merge Tools Research</h4>
      <p>Pesquisa de iniciação científica sobre ferramentas de merge e resolução de conflitos em controle de versão. Revisão sistemática de 3.689 artigos, criação de taxonomia e estudo empírico comparativo de 3 ferramentas em 39 cenários de conflito. Apresentado na <em>XXXII Mostra de Iniciação Científica e Tecnológica 2025</em>.</p>
      <p><sub>Git · C · Análise Comparativa · SLR</sub></p>
    </td>
    <td width="50%">
      <h4>🎯 Makers Hub — Audit & QA</h4>
      <p>Auditoria visual de consistência entre ambiente dev e Figma: documento estruturado com 41 issues em 17 telas, classificadas por severidade. Contribuições em frontend e integração CI/CD com Bitbucket.</p>
      <p><sub>React · Figma · Confluence · Bitbucket</sub></p>
    </td>
  </tr>
</table>

---

### 📈 GitHub Stats

<div align="center">
  <img height="155em" src="https://github-readme-stats.vercel.app/api?username=MateusMunaro&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117"/>
  <img height="155em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MateusMunaro&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117"/>
</div>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MateusMunaro&theme=github-dark-blue&hide_border=true&background=0d1117" alt="GitHub Streak" />
</p>

---

<p align="center">
  <sub>🇧🇷 Porto Alegre, RS · Análise e Desenvolvimento de Sistemas (previsão Jan/2027)</sub>
</p>
