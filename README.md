## Jérémie Bidaux

Backend & AI engineer in Lausanne, Switzerland. I build Python services that turn slow, manual workflows into one-click pipelines.

Background: biology (MSc, University of Lausanne), then 42 School Lausanne. Since then: Java at Groupe Mutuel, Python and DevOps at the University of Lausanne.

### Featured: [σ-Bridge](https://github.com/unilenlac/s-bridge)

A FastAPI service I designed and built for the University of Lausanne's ENLAC research project on ancient manuscripts (about 200 commits).

It fetches manuscript transcriptions from a DTS (Distributed Text Services) endpoint, parses the TEI-XML, tokenizes and lemmatizes Ancient Greek with **CLTK / Stanza**, aligns the manuscript variants with **CollateX**, and imports the result into the **Stemmarest** server. It replaced the local files and many manual steps of a workflow that ran from 2018 to 2025 with a single pipeline.

`Python` `FastAPI` `SQLModel` `Alembic` `CLTK` `Stanza` `httpx` `pytest` `Docker` `Podman / Quadlet` `Rocky Linux`

### Other work

- **Order-management web app (freelance, private)**: a Django app for a small business. It manages clients and orders, migrated 1,500 Excel records to SQLite, and generates courier-ready PDFs in one click. Deployed with Docker; I still maintain it.
- **[inception](https://github.com/Meltallian/inception)**: an NGINX + WordPress + MariaDB stack built from scratch with Docker Compose.
- **42 School**: C and C++ systems projects, including a Unix shell, an HTTP/1.1 server, [push_swap](https://github.com/Meltallian/push_swap), [philosophers](https://github.com/Meltallian/philosophers) and [C++ modules](https://github.com/Meltallian/CPP).

### Stack

**Languages:** Python, Java, C, C++, SQL, JavaScript, Bash, R
**Backend:** FastAPI, Django, Spring Boot, Pydantic, SQLModel
**NLP / AI:** CLTK, Stanza, Ollama
**Infrastructure:** Docker, Podman, Linux, Jenkins, SonarQube, Git
