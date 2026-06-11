# Mohd Ibadullah

Backend & ML student focused on security systems, real-time architectures, and applied NLP.
Diploma graduate (CSE) → B.Tech CSE (AI & ML) at KMIT, Hyderabad (lateral entry). Open to internships.

---

## Projects

| Project | Live | GitHub | Highlights |
|---------|------|--------|------------|
| **Prompt Injection Detection** | - | [Repo](https://github.com/mohd-ibadullah/prompt-injection-detection) | 3-model ensemble · 95.26% recall · hybrid remediation · 99.84% utility · Zenodo preprint |
| **PhishShield** | [Demo](https://phish-shield-eta.vercel.app) | [Repo](https://github.com/mohd-ibadullah/PhishShield) | 18,684 samples · 97.19% offline · ~80–85% on 100 live emails · SHAP · Chrome MV3 |
| **MusicFlow** | [Demo](https://music-flow-vqmp.vercel.app) | [Repo](https://github.com/mohd-ibadullah/MusicFlow) | 30+ REST APIs · Helmet.js · Socket.IO · Redis · collaborative filtering |

---

## Prompt Injection Detection & Remediation — LLM Email Security

**Research preprint:** [Zenodo — doi:10.5281/zenodo.20640595](https://doi.org/10.5281/zenodo.20640595)

Offline pipeline that detects prompt injections in email text and returns sanitized content for LLM agents to continue using — no external API calls.

Fine-tuned RoBERTa, SecureBERT, and DistilBERT on 5,995 samples. 3-model ensemble reaches 95.26% recall. Hybrid learned + regex remediation preserved 99.84% mean content retention on detector-flagged injected samples. Deployed via FastAPI.

Tech: Python · FastAPI · RoBERTa · SecureBERT · DistilBERT · HuggingFace Transformers · BIO tagging · Kaggle T4

---

## PhishShield — Multilingual Phishing Detection

Trained on 18,684 samples (TF-IDF + SecureBERT + MuRIL). Improved real-world detection from 42% → ~80–85% on 100 live emails (20+ edge cases fixed). FastAPI backend, fast explainability (SHAP optional), Chrome Extension (MV3), Docker CI.

Tech: Python · FastAPI · React · TypeScript · Docker · SecureBERT · MuRIL · SHAP · SQLite · Drizzle ORM · Zod · pnpm

---

## MusicFlow — Full-Stack Music Streaming

30+ REST APIs with JWT, RBAC, Helmet.js security headers, and rate limiting across listener + admin React apps. Redis cache-aside with in-memory fallback. Socket.IO real-time sync. Collaborative filtering + AI playlists (MongoDB retrieval only — no hallucinated tracks).

Tech: React 19 · Node.js · Express · MongoDB · Redis · Socket.IO · JWT · Helmet.js · Cloudinary

---

## Tech

Python · FastAPI · Node.js · Express · React · TypeScript · MongoDB · Redis · Socket.IO · Docker · JWT · HuggingFace Transformers · Scikit-learn · GitHub Actions

---

## Contact

[LinkedIn](https://www.linkedin.com/in/mohd-ibadullah-4786b640a/) · [Email](mailto:mohdibadullah24@kmit.edu.in) · [GitHub](https://github.com/mohd-ibadullah)
