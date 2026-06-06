### Andrii Dosyn

Python backend developer · STU FIIT Bratislava · focused on backend systems and ML/NLP

I work on backend systems and NLP — scraping, clustering, async pipelines. Recently started deploying on AWS EC2 and picking up Docker.

---

**Stack**

`Python` `Django · DRF` `FastAPI` `Celery · Redis` `SentenceTransformers` `spaCy`  
`MongoDB · MySQL · PostgreSQL` `Docker` `AWS EC2` `Linux` `Git` `REST API`

---

**Projects**

**[news-link](https://github.com/Dosinn/news-link)** · 🏆 JASU 2025 · 1st place (Junior Academy of Sciences of Ukraine)

Real-time news aggregator for Ukrainian media. Built a custom fine-tuned SentenceTransformer model (dos1/news-similarity-ukr) for semantic clustering — standard K-Means/DBSCAN didn't cut it for Ukrainian text. Articles are scraped asynchronously via Celery, clustered by cosine similarity, and cached in Redis. Users get personalized feeds based on a preference vector updated via EMA as they read.
`Django` `Celery` `Redis` `MongoDB` `SentenceTransformers` `AWS EC2`

---

**[autobook](https://github.com/TokyoCity0837/AutoBook)** · in progress · STU FIIT team project

Platform for writers with a social layer and AI tools. Three separate services — Java Spring Boot handles core logic, React on the frontend, and a Python/FastAPI microservice for NLP: style analysis, text suggestions, generation. I built the Python/FastAPI AI microservice, and the React/TypeScript frontend.

`FastAPI` `spaCy` `MongoDB` `MySQL`

---

📫 [LinkedIn](https://www.linkedin.com/in/andrii-dosyn-13460b411/)
