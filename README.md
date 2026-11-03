7# 💧 JalSaathi: Precision Irrigation & FAO-56 Water Advisory PWA

[![Neural Storm 2026](https://img.shields.io/badge/Event-Neural%20Storm%202026-green.svg)](https://unstop.com)
[![Track](https://img.shields.io/badge/Track-Green%20Planet%20(GP--02)-blue.svg)](https://unstop.com)
[![Python FastAPI](https://img.shields.io/badge/Backend-FastAPI%20%2F%20Python-orange.svg)](https://fastapi.tiangolo.com)
[![React PWA](https://img.shields.io/badge/Frontend-React%20%2F%20PWA-cyan.svg)](https://react.dev)

---

## 👥 Team Details
* **Team Name:** Innovexa
* **Team Leader / Member:** D. Madhumitha
* **Event:** Neural Storm 2026 (JNTUH, Hyderabad)

---

## 🌾 Problem Statement (GP-02)
Traditional agricultural irrigation methods in India often lead to severe water waste, high electricity costs, and crop stress due to lack of real-time, localized data. **JalSaathi** solves this by delivering an offline-first, voice-enabled, low-literacy Progressive Web App (PWA) that merges hyper-local weather data with rigorous **FAO-56 Penman-Monteith hydrological calculations** and **Python-backed machine learning (XGBoost)** to give precise, automated irrigation recommendations.

---

## 🚀 Key Features & Innovations
1. **"Living Field" Visual Hero UI:** Replaces boring dashboards with an interactive 2D soil-crop cross-section displaying live root zone moisture saturation and a red crop stress threshold line.
2. **Two-Way Voice Query Assistant:** Built with the Web Speech API supporting multi-lingual audio queries (English, Tamil, Hindi, Telugu) with instant text-to-speech audio feedback.
3. **Scientific FAO-56 Engine & Rain Guard:** Computes Crop Evapotranspiration ($ET_c = ET_0 \times K_c$), Total Available Water (TAW), and Readily Available Water (RAW) with an automatic 48-hour rain-risk override rule.
4. **Water Bank & Rupee Savings Tracker:** Converts water saved into actual financial metrics in Indian Rupees (₹) based on standard 5HP pump electricity tariffs.
5. **Offline PWA Sync:** Fully operational in remote rural zones via local caching (`localStorage`/IndexedDB) with seamless fallback between the local TypeScript core and the Python FastAPI backend.
6. **Panchayat / Officer Village View:** Grid map of sample village farms with color-coded stress badges and emergency priority sorting for local agricultural administrators.

---

## 🛠️ Tech Stack

### Frontend & Cloud Hosting
* **Framework:** React, Progressive Web App (PWA)
* **Styling & Icons:** Tailwind CSS, Lucide React, Framer Motion
* **APIs & Voice:** Open-Meteo Weather API, Web Speech API (`webkitSpeechRecognition`, `SpeechSynthesis`)
* **Deployment Platform:** Raccoon AI Cloud (`3000.dev.raccoonai.tech`)

### Backend & AI/ML Components (Python)
* **Primary Language:** Python 3.10+
* **Framework:** FastAPI (`main.py`)
* **Data Science & ML:** NumPy, scikit-learn, XGBoost
* **Hosting:** Hugging Face Spaces / Uvicorn Server

---
## 🤖 AI Tools & Platforms Used
In compliance with hackathon guidelines, the following AI tools and platforms were utilized during the development and deployment of **JalSaathi**:
* **Raccoon AI:** Utilized as the core development environment, containerized cloud execution engine, and live deployment platform (`3000.dev.raccoonai.tech`).
* **Cursor & ChatGPT:** Used for structuring modular FastAPI endpoints, debugging FAO-56 hydrological formulas, and generating responsive React component states.
* **v0 (v0.dev):** Used to rapidly prototype the earthy-premium mobile UI/UX layouts, "Living Field" visual cross-section, and micro-interactions.

---

## ⚙️ Setup & Installation Instructions

### 1. Clone the Repository
```bash
git clone [https://github.com/madhumitha9971/jalsaathi-precision-irrigation.git](https://github.com/madhumitha9971/jalsaathi-precision-irrigation.git)
cd jalsaathi-precision-irrigation

* **Website URL:** `[https://lifted-anointed-hawk.3000.dev.raccoonai.tech/]
* **Topics/Tags:** `precision-agriculture`, `fao-56`, `fastapi`, `pwa`, `agritech`, `neural-storm-2026`, `raccoon-ai`
