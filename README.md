## Jérémie Bidaux

**Backend & Research Software Engineer** based near Lausanne, Switzerland (Renens).  
I build Python and Java backend services, scientific data pipelines, and containerized Linux deployments.

Background: MSc in Biology (University of Lausanne) and software engineering at **42 Lausanne** (C/C++, Unix systems). Professionally: enterprise Java at **Groupe Mutuel**, then Python backend & Linux DevOps at the **University of Lausanne**.

[LinkedIn](https://linkedin.com/in/YOUR_HANDLE) · [Email](mailto:jeremie.bidaux@gmail.com)

---

### Featured: [σ-Bridge](https://github.com/unilenlac/s-bridge)

A production FastAPI service I architected and deployed for the University of Lausanne's ENLAC research project on ancient manuscripts (~200 commits).

- Fetches manuscript transcriptions from a **DTS** (Distributed Text Services) endpoint, parses TEI-XML, tokenizes and lemmatizes Ancient Greek with **CLTK / Stanza** / *Ollama*, aligns textual variants with **CollateX**, and imports results into **Stemmarest**.
- Replaced a 7-year local-file workflow (2018–2025) with a centralized, server-hosted REST API and single-click pipeline.
- Deployed on **Rocky Linux** using rootless **Podman**, **Quadlet**, and **systemd** for declarative restarts and crash recovery.

`Python` `FastAPI` `Pydantic` `SQLModel` `Alembic` `Stanza` `httpx` `pytest` `Podman / Quadlet` `systemd` `Rocky Linux`

---

### Currently building: [unplug](https://github.com/Meltallian/unplug)

An active side project built with a friend *(adjust: e.g., owning the Python/FastAPI backend, async pipeline, and deployment)*: paste a YouTube link and get a playable guitar chord sheet.

- **Chord recognition:** Transformer model (BTC) decoded onto song bars.
- **Rhythm & structure:** Tempo, time signature, and bar tracking, including mid-song meter changes (6/8 ↔ 4/4).
- **Word-level alignment:** Lyrics aligned via **Whisper** so chord changes sit directly over the right syllable.
- **Engraved output:** MEI → Verovio → SVG rendering, interactive chord editor, capo/transposition, and PDF export.

`Python` `FastAPI` `Celery` `Redis` `PostgreSQL` `PyTorch` `Whisper` `Docker Compose`

---

### Other work

- **Order-management web app (Freelance, private):** Production **Django / Python** platform for a small business. Migrated 1,500+ legacy Excel records to a normalized **SQLite** database and automated courier-ready PDF generation. Deployed via **Docker** on a private Linux server (Synology); actively maintained.
- **[inception](https://github.com/Meltallian/inception):** NGINX + WordPress + MariaDB stack built from scratch with Docker Compose.
- **42 Lausanne:** Systems programming in C/C++, including a Unix shell (**Minishell**), an RFC 7230 HTTP/1.1 server (**Webserv**), a full-stack web app (**Transcendance**), plus [push_swap](https://github.com/Meltallian/push_swap), [philosophers](https://github.com/Meltallian/philosophers), and [C++ modules](https://github.com/Meltallian/CPP).

---

### Stack

- **Languages:** Python, Java, C, C++, SQL (PostgreSQL, SQLite), JavaScript, Bash, R
- **Backend & Data:** FastAPI, Django, Pydantic, SQLModel, Alembic, Celery, Redis, REST APIs, pytest
- **NLP & ML Tooling:** Stanza, CLTK, Ollama, PyTorch, Whisper
- **Infrastructure & Quality:** Linux (Rocky), Docker, Podman / Quadlet, systemd, Jenkins, SonarQube, Maven, Git
