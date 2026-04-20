## Jacob Manhardt
 
Senior Computer Science student at Syracuse University (B.S., May 2026). I build backend systems — mostly Python/FastAPI services with Postgres, deployed on AWS with Docker and GitHub Actions CI/CD. Open to new-grad and summer 2026 SWE roles, relocation-friendly.
 
📍 Syracuse, NY · 📫 jemanhardt@comcast.net · [LinkedIn](https://www.linkedin.com/in/jacob-manhardt/)
 
---
 
### What I'm working on
 
**[Email Application Tracker API](https://github.com/manhardt23/Email-Application-Tracker-API)** — a production REST API that monitors my inbox over IMAP, classifies job-application emails with an LLM, and tracks status across a normalized Postgres schema. Runs on EC2 behind a CI/CD pipeline in GitHub Actions that lints, tests (83% coverage), builds a multi-stage Docker image, pushes to ECR, and deploys on merge. Provider-agnostic LLM layer (Groq in prod, Ollama for local dev) with a keyword pre-filter that eliminates ~40% of inference calls. Python · FastAPI · SQLAlchemy · Alembic · Postgres · Docker · AWS
 
**[Head First Kitchen](https://github.com/manhardt23/Head-First-Kitchen)** — a real-time kitchen simulator in C++ modeling concurrent order processing across multiple cooking stations. 15+ classes, 5 GoF design patterns (Strategy, State, Observer, Factory, Template Method), UML-first architecture. Built for OOP in C++ coursework. C++ · OOP · Design Patterns · Concurrency
 
**[Ticket to Ride Route Optimizer](https://github.com/manhardt23/Ticket-to-Ride-Route-Optimizer)** — graph-based route solver using NetworkX and Dijkstra's. Evaluates 30M+ route combinations against trip-card constraints; caching brings full-run time from ~2 minutes to <100 ms. Python · NetworkX · Graph algorithms
 
---
 
### Stack
 
**Languages:** Python · C++ · C · Java · JavaScript/TypeScript · SQL · Bash
**Backend:** FastAPI · SQLAlchemy · Alembic · REST · pytest · repository pattern
**Data:** PostgreSQL · SQL Server · schema design · query optimization
**Cloud & DevOps:** AWS (EC2, ECR, S3, IAM) · Docker · GitHub Actions · Linux · Git
**AI/ML:** LLM integration (Groq/Llama 3, Ollama) · TF-IDF · NumPy · NetworkX
 
---
 
### What I'm learning next
 
Distributed systems fundamentals. Currently reading *Designing Data-Intensive Applications* (2nd ed., Kleppmann) and extending the Email Tracker into a two-service architecture with a message queue between the ingestion worker and the API — a chance to apply the replication, partitioning, and fault-tolerance ideas from the book to something I actually run. Picking up Go on the side.
 
---
 
*If you're a recruiter or engineer at a company hiring new-grad backend engineers, I'd love to hear from you — jemanhardt@comcast.com.*
 
