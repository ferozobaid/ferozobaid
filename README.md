# Hi there, I'm Feroz

I hold a Master of Management in Analytics and AI from McGill University, with a focus on machine learning, Artificial Intelligence, and analytics.

I see myself as an AI & Analytics professional with experience across CPG, commercial strategy, and finance. Before McGill, I worked in commercial strategy and analytics at British American Tobacco and S&P Global Market Intelligence. My projects span applied ML, LLM-powered applications, causal inference, NLP, recommendation systems, and executive BI.

## Featured Projects

### [Synthesis](https://github.com/ferozobaid/Synthesis) — AI-powered interview readiness platform · [Live app](https://synthesis-sand.vercel.app)

A single platform for interview preparation: resume-to-job-description fit analysis, conversational AI voice interviews, behavioural coaching, strategy case simulations, and technical interview rounds, aggregated into one readiness dashboard.

- **Stack:** Next.js 14 (App Router), TypeScript, Tailwind CSS, deployed on Vercel
- **LLM layer:** Anthropic Claude via the official SDK for answer evaluation, question generation, and post-call scoring
- **Voice:** live conversational interviews through Vapi, with Upstash Redis holding session state across turns
- **Resume fit scoring:** a hybrid method blending deterministic rule-based requirement matching (25%) with local semantic matching (75%), grounded in a committed O\*NET taxonomy subset, with an automatic rules-only fallback
- **Embeddings:** BGE-small running locally via ONNX — no paid embedding API
- **Case interviews:** a finite-state-machine interviewer that moves through clarification, structuring, analysis, and recommendation stages against committed case definitions with exhibits and hint ladders
- **Document handling:** PDF and DOCX resume parsing
- **Validation:** the fit-scoring method was selected through a 353-resume / 269-job-description study plus a 54-pair human-labelled comparison, backed by a Vitest suite of ~85 test files

### [world-cup-predictor-lab](https://github.com/ferozobaid/world-cup-predictor-lab)

A Next.js + Python ML lab for the 2026 FIFA World Cup. It combines calibrated CatBoost, logistic regression, Elo + Poisson modeling, Monte Carlo simulation, and an LLM-powered analyst brief into an interactive prediction app deployed on Vercel.

## Other Work

- **[fifa22-wage-prediction](https://github.com/ferozobaid/fifa22-wage-prediction)** — End-to-end ML pipeline on FIFA 22 player data that goes beyond wage prediction into causal inference, with preprocessing, feature engineering, model selection, hyperparameter tuning, and CausalML/DoWhy analysis.
- **[ml-stock-selection-strategy](https://github.com/ferozobaid/ml-stock-selection-strategy)** — ML-based long-only small/mid-cap US stock-selection strategy, backtested out-of-sample from 2010–2024 against the S&P 500.
- **[readmission-risk-prediction](https://github.com/ferozobaid/readmission-risk-prediction)** — Calibrated 30-day hospital readmission risk model with patient-grouped splits, SHAP explanations, and a fairness audit.
- **[pharmacovigilance-nlp](https://github.com/ferozobaid/pharmacovigilance-nlp)** — NLP pipeline classifying adverse drug events from free text using TF-IDF, scispaCy NER features, and supervised learning.
- **[consumer-market-insights-dashboard](https://github.com/ferozobaid/consumer-market-insights-dashboard)** — Sanitized executive Power BI dashboard concept for monthly market reporting, KPI governance, category performance, and commercial insights.

## Toolkit

Python · TypeScript · SQL · SAS · scikit-learn · CatBoost · SHAP · scispaCy · CausalML / DoWhy · Next.js / React · Claude API · Power BI · Vercel

---

Open to opportunities in AI/ML, analytics, AI product, and technical consulting.
