<div align="center">

![Header](https://capsule-render.vercel.app/api?type=rect&color=0:111827,100:312E81&height=155&text=Kshitij%20Kataria&fontColor=F9FAFB&fontSize=38&fontAlignY=42&desc=Software%20Engineering%20%7C%20AI%2FML%20%7C%20Full-Stack%20Development&descColor=C4B5FD&descSize=17&descAlignY=66)

[![B.Tech IT](https://img.shields.io/badge/B.Tech-Information%20Technology-312E81?style=flat-square)](#education)
[![NSUT](https://img.shields.io/badge/NSUT-CGPA%208.62%2F10-4338CA?style=flat-square)](#education)
[![Location](https://img.shields.io/badge/Location-New%20Delhi%2C%20India-4F46E5?style=flat-square)](#contact)

[![Email](https://img.shields.io/badge/Email-kshitijk2128%40gmail.com-374151?style=flat-square&logo=gmail&logoColor=white)](mailto:kshitijk2128@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kshitij%20Kataria-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kshitij-kataria)
[![GitHub](https://img.shields.io/badge/GitHub-kshitij3103-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kshitij3103)
[![LeetCode](https://img.shields.io/badge/LeetCode-kshitijk2128-6D28D9?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/kshitijk2128/)

</div>

---

## Profile

Software engineering student at Netaji Subhas University of Technology, pursuing a B.Tech in Information Technology. My work focuses on distributed systems, event-driven microservices, secure full-stack applications, and applied AI/ML.

I am currently a Summer Intern at the Defence Research and Development Organisation, contributing to communication- and signal-processing-related projects at the Sanchar Lab, Scientific Analysis Group.

---

## Education

| Institution | Qualification | Duration | Performance |
|:--|:--|:--|:--|
| Netaji Subhas University of Technology | B.Tech in Information Technology | 2023 – 2027 | CGPA: **8.62 / 10** |
| CBSE | Class XII | 2021 – 2022 | **97%** |
| CBSE | Class X | 2019 – 2020 | **96.4%** |

---

## Experience

### Summer Intern · Defence Research and Development Organisation (DRDO)

**Sanchar Lab, Scientific Analysis Group (SAG)**  
`May 2026 – Present`

- Assisted in research and development activities on communication- and signal-processing-related projects.
- Worked on an AI-assisted automated debugging framework using locally deployed LLMs to interpret telemetry data and generate structured corrective actions through JSON-based interfaces.
- Processed and validated structured data exchanged across communication and analysis pipelines using JSON, XML, and Protocol Buffers, supporting interoperability between software components.

`AI/ML` `LLMs` `Telemetry Analysis` `JSON` `XML` `Protocol Buffers`

---

## Featured Projects

<details open>
<summary><b>CronaFlow — Resilient Distributed Task Scheduler</b></summary>

<br/>

[![Repository](https://img.shields.io/badge/Repository-View%20on%20GitHub-312E81?style=flat-square&logo=github&logoColor=white)](https://github.com/kshitij3103/CronaFlow)

| Area | Details |
|:--|:--|
| **Stack** | Spring Boot, React, Redis, MongoDB, JWT, Docker, Spring WebFlux |
| **Throughput** | 500+ tasks/sec |
| **Scheduling Latency** | Sub-1.3s average |
| **Reliability** | Leader election, Redis distributed locks, DAG recovery, retries, and Dead Letter Queue |

- Architected a distributed task scheduler using Spring Boot, MongoDB, and Redis Streams.
- Mitigated duplicate execution across horizontally scaled nodes through active-passive leader election and Redis distributed locks.
- Engineered fault-tolerant Directed Acyclic Graph pipelines with automatic orphaned-task recovery, configurable retries, and a Dead Letter Queue for permanent failures.
- Built non-blocking Spring WebFlux workers for SMTP dispatch, Gemini API data processing, and a GraphQL-based LeetCode scraper.
- Developed a responsive React frontend secured with custom JWT authentication for real-time queue and workflow monitoring.

</details>

<details>
<summary><b>AI Powered Fitness Tracker App</b></summary>

<br/>

[![Repository](https://img.shields.io/badge/Repository-View%20on%20GitHub-312E81?style=flat-square&logo=github&logoColor=white)](https://github.com/kshitij3103/Fitness-Microservices)

| Area | Details |
|:--|:--|
| **Stack** | Spring Boot, Spring Cloud, React, Docker, RabbitMQ, Keycloak |
| **Persistence** | PostgreSQL and MongoDB |
| **Architecture** | Event-driven microservices |
| **Security** | Centralized OAuth2/OIDC authentication through Keycloak |

- Built an event-driven fitness web application using Spring Boot microservices and a React frontend, containerized with Docker Compose.
- Configured centralized configuration and service discovery using Spring Cloud Config and Eureka.
- Decoupled inter-service communication through RabbitMQ message queues.
- Used PostgreSQL and MongoDB for polyglot persistence across services.
- Secured REST APIs and user sessions through Keycloak.
- Integrated Google Gemini API to analyze user health metrics and generate personalized fitness recommendations.

</details>

<details>
<summary><b>ALS Disease Progression Prediction</b></summary>

<br/>

[![Repository](https://img.shields.io/badge/Repository-View%20on%20GitHub-312E81?style=flat-square&logo=github&logoColor=white)](https://github.com/kshitij3103/ALS-Neuro-Fuzzy-Model)

| Area | Details |
|:--|:--|
| **Stack** | Python, PyTorch, Scikit-Learn, XGBoost, ANFIS, Fuzzy Logic |
| **Model** | 10-cluster ANFIS ensemble |
| **Evaluation** | 12 modeling combinations benchmarked |
| **Results** | Pearson correlation: ~0.42 · RMSD: ~0.53 |

- Developed an end-to-end PyTorch pipeline to forecast ALS progression rates using a 10-cluster ANFIS ensemble trained through K-Means clustering, back-propagation, and least-squares estimation.
- Engineered longitudinal features across six clinical domains with dynamic IQR-based outlier removal and fold-specific median imputation to prevent data leakage during cross-validation.
- Benchmarked the ANFIS framework against XGBoost, Random Forest, and linear baselines using RFE and Pearson feature selection.
- Automated feature-importance charts and clinical-rule tables using Pandas and Seaborn.

</details>

---

## Technical Skills

<div align="center">

[![Skills](https://skillicons.dev/icons?i=java,cpp,python,js,spring,react,tailwind,postgres,mongodb,mysql,redis,docker,rabbitmq,git,github,vscode,idea,postman&theme=dark&perline=9)](https://skillicons.dev)

</div>

| Category | Technologies |
|:--|:--|
| **Languages** | Java, C++, Python, JavaScript |
| **Frameworks & Libraries** | Spring Boot, Spring Cloud, React, Tailwind CSS |
| **Databases** | PostgreSQL, MongoDB, MySQL, Redis |
| **Tools & IDEs** | Docker, RabbitMQ, Keycloak, Git, GitHub, VS Code, IntelliJ IDEA, Postman |
| **Relevant Coursework** | Data Structures & Algorithms, Design and Analysis of Algorithms, DBMS, Operating Systems, Software Engineering, Soft Computing, OOPS |

---

## Achievements & Activities

| Recognition | Details |
|:--|:--|
| Adobe Hackathon 2025 | Secured a top 5% rank among 100,000+ teams. |
| Model United Nations | Secured distinction in intra-school and inter-school conferences. |
| Debate | Actively participated in inter-school debate competitions, demonstrating communication and critical-thinking skills. |

---

## Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-kshitijk2128%40gmail.com-374151?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kshitijk2128@gmail.com)
[![Phone](https://img.shields.io/badge/Phone-%2B91%208920393774-374151?style=for-the-badge&logo=phone&logoColor=white)](tel:+918920393774)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kshitij%20Kataria-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kshitij-kataria)
[![GitHub](https://img.shields.io/badge/GitHub-kshitij3103-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kshitij3103)

</div>

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=rect&color=0:111827,100:312E81&height=65&section=footer)

</div>
