<!-- HEADER -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Sisnando%20Junior&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Senior%20Data%20Engineer%20%C2%B7%20Python%20%C2%B7%20AI-Augmented%20DataOps&descSize=18&descAlignY=60" alt="Header"/>

<a href="https://github.com/nandodevs">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Building+resilient+data+platforms;Python+%C2%B7+dbt+%C2%B7+Airflow+%C2%B7+DuckDB;Data+contracts+%2B+observability+by+design;Putting+AI+to+work+in+data+pipelines" alt="Typing SVG"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sisnando-junior)
[![Portfolio](https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=notion&logoColor=white)](https://brook-bay-469.notion.site/sisnando-portfolio)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@sis_data)
![Profile views](https://komarev.com/ghpvc/?username=nandodevs&style=for-the-badge&color=0EA5E9&label=PROFILE+VIEWS)

</div>

---

## 🧭 About

I build **scalable, observable, contract-driven data platforms**. I bring software engineering rigor (typing, tests, CI/CD) to the Modern Data Stack, and I use AI to remove manual work from the data lifecycle.

```python
from dataclasses import dataclass, field

@dataclass
class SisnandoJunior:
    role: str = "Senior Data Engineer @ Zenvia"
    languages: tuple = ("Python", "SQL")
    paradigms: tuple = ("Medallion", "Event-Driven", "Data Contracts", "DataOps")
    obsessions: list = field(default_factory=lambda: [
        "Data quality & observability",
        "Type-safe pipelines",
        "Developer experience for data teams",
        "AI-augmented workflows",
    ])

    def mission(self) -> str:
        return "Make data trustworthy, fast and boring (in production)."
```

<table>
<tr>
<td width="50%" valign="top">

### 🏗️ What I do
- Multi-tenant ingestion engines
- Dimensional and layered modeling
- End-to-end governance and lineage
- CI/CD, testing and modular codebases for data

</td>
<td width="50%" valign="top">

### 🛡️ What I care about
- Automated tests and anomaly detection
- SLA tracking and Slack alerting
- `Elementary` + `dbt tests`
- Schemas validated with `Pydantic`

</td>
</tr>
</table>

---

## 🎯 Current Focus

| | Pillar | Focus & Tech |
| :-: | :-- | :-- |
| 🐍 | **Modern Python for Data** | `DuckDB` · `Polars` · `Pydantic` · `uv` / `poetry` · `pytest` |
| 🤖 | **AI-Augmented DataOps** | LLM-generated docs, lineage audits, smart schema mapping, AI-assisted code review |
| 🔄 | **Automated ELT & Ingestion** | Custom Python extractors, Airbyte connectors, rate-limit handling, idempotent loads |
| 🛡️ | **Observability & Governance** | Anomaly detection, drift monitoring, automated metadata pipelines |

---

## 🧩 Reference Architecture

```mermaid
flowchart LR
    A[APIs / DBs / Files] -->|Airbyte · Python extractors| B[(Bronze<br/>raw)]
    B -->|dbt · Pydantic contracts| C[(Silver<br/>clean)]
    C -->|dbt models| D[(Gold<br/>business)]
    D --> E[BI · APIs · ML]
    F{{Airflow / Astronomer}} -.orchestrates.-> B
    F -.-> C
    F -.-> D
    G[Elementary · dbt tests] -.monitors.-> C
    G -.-> D
    G -->|alerts| H[Slack]
    I[LLM assistants] -.docs · lineage · schema mapping.-> C
```

---

## 🛠️ Tech Stack

<div align="center">

**Languages & Python ecosystem**

<img src="https://skillicons.dev/icons?i=python,fastapi,docker,git,github,linux,bash&theme=dark" alt="python stack"/>

![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white)

**Orchestration, transformation & ingestion**

![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Astronomer](https://img.shields.io/badge/Astronomer-2D2D2D?style=flat-square&logo=astronomer&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Elementary](https://img.shields.io/badge/Elementary-FF4081?style=flat-square)
![Airbyte](https://img.shields.io/badge/Airbyte-6132F9?style=flat-square&logo=airbyte&logoColor=white)

**Cloud, warehouses & databases**

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

**AI & Automation**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![LLM](https://img.shields.io/badge/LLM_Workflows-8B5CF6?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-111827?style=flat-square)

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎬 [kdrama_analytics_project](https://github.com/nandodevs/kdrama_analytics_project)
End-to-end analytics pipeline: ingestion, modeling and data tests.

`Python` `dbt` `Airflow` `PostgreSQL`

</td>
<td width="50%" valign="top">

### 📊 [investimentos-govbr-dataeng](https://github.com/nandodevs/investimentos-govbr-dataeng)
Engineering and observability over public federal investment data.

`Python` `Pandas` `SQL` `Docker`

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=nandodevs&theme=tokyonight&hide_border=true" alt="Streak"/>

<br/>

<img src="https://img.shields.io/github/followers/nandodevs?style=for-the-badge&logo=github&color=0EA5E9&labelColor=0F172A" alt="Followers"/>
<img src="https://img.shields.io/github/stars/nandodevs?style=for-the-badge&logo=github&color=0EA5E9&labelColor=0F172A" alt="Stars"/>
<img src="https://img.shields.io/github/commit-activity/y/nandodevs/kdrama_analytics_project?style=for-the-badge&logo=git&color=0EA5E9&labelColor=0F172A&label=commits%2Fyear" alt="Commits"/>

</div>

---

<div align="center">

### 💬 Let's connect

Open to talk about **Data Reliability**, **Analytics Engineering**, **Python for Data** and **AI in the data stack**.

[![LinkedIn](https://img.shields.io/badge/Message_me_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sisnando-junior)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,100:0F2027&height=100&section=footer" alt="Footer"/>

</div>
