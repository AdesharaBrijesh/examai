# ExamAI

ExamAI is an AI-driven assessment platform designed to **generate, conduct, and evaluate exams** using modern GenAI architectures.  
It supports both:
- **New exam generation from course material**, and
- **Existing question paper evaluation** (previous-year / mock exams).

The system is built with performance, explainability, and real-world exam workflows in mind.

---

## Core Capabilities

### Generate
- Retrieval-Augmented Generation (RAG) over course PDFs, notes, and books
- Deterministic blueprint-based exam structure
- Multi-LLM generation and verification
- Reference answer and rubric generation

### Conduct
- React-based custom exam platform
- Offline-safe answer storage (IndexedDB)
- Automated MCQ exams via Google Forms integration
- Section-wise submission and evaluation

### Evaluate
- Instant MCQ grading
- Semantic grading for descriptive answers
- Handwritten answer support (OCR/HTR – Phase 2)
- Explainable scores with evidence tracing

---

## Modes of Operation

### Mode A: Exam Generation
Generate a new exam from course content and topics.

### Mode B: Existing Paper Mode
Use an existing question paper as-is and generate:
- Reference answers
- Rubrics
- Automated evaluation pipeline

> Existing question papers are **never used to generate new exams**.

---

## Tech Stack (MVP)

**Backend**
- Python, FastAPI
- LangChain
- FAISS
- Redis
- PostgreSQL

**AI / ML**
- LLMs (API-based initially)
- sentence-transformers
- RAG pipeline

**Frontend**
- React
- IndexedDB (offline caching)

**Infra**
- Docker
- GitHub Actions

---

## Contributors
- Brijesh Adeshara [@AdesharaBrijesh](https://github.com/AdesharaBrijesh)
- Swayam Yagnik [@nerd78](https://github.com/nerd78)

---

## License
MIT (can be changed later)
