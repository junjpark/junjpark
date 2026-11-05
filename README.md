## Hi, I'm Justin (Junyoung) Park
 
I study **Computer Science + Physics at Washington University in St. Louis** and graduate in **May 2027**.
This semester I'm abroad at **HKUST**, taking AI/ML coursework.
I like building data-driven tools that hold up under real data like calibrated models, validated pipelines and honest evaluation.
 
**I'm looking for new-grad software engineering and ML roles starting in 2027.**
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Junyoung_(Justin)_Park-0A66C2?style=flat)](https://www.linkedin.com/in/junyoung-justin-park/)
[![Email](https://img.shields.io/badge/Email-you%40example.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:junjpark02@gmail.com)
 
---
 
### Featured projects
 
#### [lol-game-review](https://github.com/junjpark/lol-game-review) · Python · XGBoost
A chess.com-style automated game review for League of Legends. It estimates each team's win probability minute by minute, flags the moments that swung the game, and separates the player's own plays from what happened elsewhere on the map.
- Resumable, rate-limited Riot API pipeline: **~20,000 ranked matches → ~600,000 game states**, with each match checked against Riot's official end-of-game totals
- Calibrated XGBoost win-probability model: **0.8-point average calibration error on 5,739 unseen matches**, with pass/fail release criteria fixed before training
- Hypothesis-driven feature work: found that gold held by one player is worth **11–14 pts** more than the same lead spread across the team, then confirmed it out of sample
- Harness-engineered for AI coding agents (Claude Code): a short `CLAUDE.md` context map of hard constraints, pointing agents to the right doc only when a task needs it
- A Claude Code hook blocks irreversible agent actions (git, data collection, deleting data or models, the one-time holdout evaluation); tests enforce the review's wording rules, and golden-output tests freeze review output
- Every task starts with a contract (objective, what must not change, evidence for "done", what needs owner approval); every session ends with a change receipt in `docs/sessions.md`
- Every failure is logged in `docs/failures.md` with the new test, hook or CI step that now catches it
- Each analysis has its contract committed before any code, then passes an automated gate and an independent reviewer agent that sees the contract, script and results but not the conclusions
#### [rebalance](https://github.com/junjpark/rebalance) · New Balance Hackathon · Gemini 2.5 Flash
A computer-vision tool for diagnosing shoe damage, prototyped in **3 hours**.
- Classifies shoe damage with **confidence-scored bounding-box localization** using Gemini 2.5 Flash
- Heatmap dashboard across **6 wear zones** for personalized fit recommendations, repurposed as an automated return-assessment engine for the **60M+ shoppers** without access to in-store 3D scanning
#### [GrubU](https://github.com/junjpark/GrubU) · Swift · Firebase
An iOS marketplace for campus meal points. Students who are short on meal points request meals from students with a surplus and pay them back in USD.
- Native Swift app backed by Firebase (Firestore and Cloud Functions)
- Built but never launched because of university dining policy
#### [cory](https://github.com/junjpark/cory) · React · FastAPI · PostgreSQL · team project
An AI choreography-analysis tool for dancers. It skeletonizes an uploaded dance video and supports notes left directly on the video, mirrored practice views, music sync, and similarity scoring of a practice video against the original.
 
---
 
### Tech
 
**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat&logo=ruby&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![Racket](https://img.shields.io/badge/Racket-9F1D20?style=flat&logo=racket&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
 
**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
 
**Frameworks & Libraries**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat)
 
**Databases & Tools**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat&logo=firebase&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth-EB5424?style=flat)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Agile](https://img.shields.io/badge/Agile-0052CC?style=flat)
 
---

### Outside of cs
🎮 Gaming - I was in the Top 50 best Overwatch players in the nation · 🎻 Classical music - I played viola for 10 years· ⚽ Soccer - Barca fan
