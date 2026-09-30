Paste this into the `README.md` file in your [PIU2003/PIU2003](https://github.com/PIU2003/PIU2003) repository. GitHub shows that file at the top of your profile.

````markdown
<div align="center">

# Piumini Abeysinghe

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=20&duration=2800&pause=1400&color=0F766E&center=true&vCenter=true&width=720&height=36&lines=A+request+comes+in.+I+build+the+part+that+decides+where+it+goes." alt="A request comes in. I build the part that decides where it goes." />

**BSc (Hons) Information Technology** · Horizon Campus, Sri Lanka

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/piumini-abeysinghe-6870a5303)
[![Email](https://img.shields.io/badge/Email-0F766E?style=flat-square&logo=gmail&logoColor=white)](mailto:piuminiabeysinghe2003@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-111827?style=flat-square&logo=tryhackme&logoColor=9fef00)](https://tryhackme.com/p/piuminiabeysinghe2003)

</div>

```text
open to     Software Engineering internship
focus       AI applications · backends · system design
building    agents that route, services that move state
```

A health question should reach a health agent. A medicine reminder should land in a database and fire on time. A parcel should change status on a queue, then show up in the right service. That handoff is the part of software I like most.

I am an IT undergraduate in Sri Lanka, looking for a software engineering internship where I can take that kind of system into production and learn distributed systems, cloud, and design from people who ship it.

---

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### [CareMate AI](https://github.com/PIU2003/caremate-agentic-ai)

A multi-agent companion for elderly care. A coordinator reads each message and hands it to a specialist: health advice, medicine reminders, conversation, summaries, or an emergency alert.

Health answers are planned, retrieved, and reflected on before they go out. The knowledge base is 22 documents, and the last retrieval check hit **5/5**. Reminders stay in SQLite and can raise a desktop notification. If the reasoning model is unavailable, routing falls back to Groq.

[Source](https://github.com/PIU2003/caremate-agentic-ai) · [Live demo](https://caremate-ai.streamlit.app/)

`Python` `LangGraph` `Streamlit` `Groq` `FAISS` `SQLite`

</td>
<td width="50%" valign="top">

### [ParcelGO](https://github.com/PIU2003/delivery-service)

A team-built parcel platform. Parcel, Courier, Delivery, and Auth sit behind Spring Cloud Gateway, with an HTML/JS dispatch console for assign, pickup, complete, and track.

The door is JWT plus a key per service. RabbitMQ carries status changes. Redis rate-limits the gateway. Each domain keeps its own MongoDB, and Docker Compose brings the whole stack up together.

[Source](https://github.com/PIU2003/delivery-service)

`Java` `Spring Cloud` `MongoDB` `RabbitMQ` `Redis` `Docker`

</td>
</tr>
</table>

**Also shipped**

- **Employee task desk** — a Flask app for employee records, task assignment with deadlines, and status tracking. HTML views, JSON storage.
- **[Quiz platform](https://github.com/PIU2003/quiz-db-devops-assignment)** — team project where I owned deployment: Render, environment variables, production MySQL, and a Docker Compose setup for PHP and the database. [Live](https://quiz-db-devops-assignment.onrender.com)

---

## How the pieces fit

| | What I reach for | Where it shows up |
| --- | --- | --- |
| **Route** | A coordinator, a gateway, a clear owner for each request | LangGraph specialists · Spring Cloud Gateway |
| **Remember** | State that survives the request | SQLite reminders · MongoDB per service · Redis limits |
| **Talk** | Work that should not block the caller | RabbitMQ status events · model fallback when an API drops |
| **Show** | A surface a person can actually use | Streamlit chat · ParcelGO dispatch console |

---

## Toolkit

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)

![LangGraph](https://img.shields.io/badge/LangGraph-0F766E?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Spring](https://img.shields.io/badge/Spring%20Boot%20%2F%20Cloud-6DB33F?style=flat-square&logo=springboot&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## On the record

| | |
| --- | --- |
| **Study** | BSc (Hons) Information Technology, Horizon Campus · Nov 2023 – present |
| **English** | Diploma in English, Lexicon English Academy · 2021 – 2022 |
| **Python** | Python for Beginners, University of Moratuwa (CODL) · Feb 2025 · `v46UrCgl8G` |
| **Mobile** | Mobile Application Development in Kotlin, Leo Club of University of Sri Jayewardenepura · Dec 2025 |
| **Labs** | [TryHackMe](https://tryhackme.com/p/piuminiabeysinghe2003) · 31 hands-on labs in networking, Nmap, and pentesting fundamentals · Top 20% |

---

## GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=PIU2003&show_icons=true&hide_border=true&bg_color=0B1220&title_color=5EEAD4&text_color=E2E8F0&icon_color=2DD4BF&ring_color=14B8A6" alt="Piumini's GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PIU2003&layout=compact&hide_border=true&bg_color=0B1220&title_color=5EEAD4&text_color=E2E8F0&langs_count=6" alt="Top languages" />

</div>

<div align="center">

Open to a conversation about an internship, a project, or a system you are designing.

**piuminiabeysinghe2003@gmail.com**

</div>
````
