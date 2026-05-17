<h1 align="center">Hi there, I'm Feroz 👋</h1>

<p align="center">
  <strong>Analytics · Machine Learning · BI · AI-Powered Decision Products</strong>
</p>

<p align="center">
  <a href="https://github.com/ferozobaid"><img src="https://img.shields.io/badge/GitHub-ferozobaid-181717?logo=github&logoColor=white" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/McGill%20MMA-2026-D7141A" alt="McGill MMA"/>
  <img src="https://img.shields.io/badge/Open%20to-Analytics%20%7C%20BI%20%7C%20DS%20%7C%20AI%20Product-2E86AB" alt="Open to roles"/>
</p>

---

## About me

I'm a **Master of Management in Analytics** candidate at **McGill University** (2026) with five years at **British American Tobacco** in commercial and trade-marketing analytics across the Asia-Pacific region.

I build **usable data products** — not just models. The line I try to hold across every project:

> *Business context first → analytics → technical implementation that someone can actually open, read, and act on.*

That means calibrated ML that ships behind a typed frontend, BI dashboards that a senior leader can read in 90 seconds, and recommendation systems that explain themselves instead of hiding behind a black box.

---

## Featured projects

### ⚽ [world-cup-predictor-lab](https://github.com/ferozobaid/world-cup-predictor-lab)
> *Next.js + Python ML lab for the 2026 FIFA World Cup — four model lenses, 100K-run Monte Carlo bracket simulator, and an LLM-powered football-pundit analyst brief.*
- **Stack:** CatBoost (calibrated), Logistic Regression, Elo + Poisson xG, Next.js, TypeScript, OpenAI API, Vercel
- **Why it matters:** End-to-end ML productisation — offline training in Python → static JSON artifacts → typed inference in the browser → cached LLM explanations. Ships, doesn't just train.
- **Live:** [world-cup-predictor-lab.vercel.app](https://world-cup-predictor-lab.vercel.app)

### ⚽ [fifa22-wage-prediction](https://github.com/ferozobaid/fifa22-wage-prediction)
> *End-to-end ML pipeline (Géron-style) + causal inference on 19K FIFA 22 players — what predicts wages, and what actually causes wage uplift.*
- **Stack:** scikit-learn, XGBoost, GridSearchCV / RandomizedSearchCV, **CausalML** (T-Learner), **DoWhy** (structural causal model)
- **Why it matters:** Most ML projects stop at prediction. This one asks the harder question — *if you raise Composure by 5 points, what's the wage effect?* — and validates with placebo and random-cause refutations.

### 🏥 [readmission-risk-prediction](https://github.com/ferozobaid/readmission-risk-prediction)
> *Calibrated 30-day readmission risk model on 101K diabetic-patient encounters across 130 U.S. hospitals — with SHAP explanations and a fairness audit.*
- **Stack:** XGBoost, isotonic calibration, SHAP, `GroupedStratifiedKFold`, `scale_pos_weight`
- **Headline numbers:** PR-AUC 0.221 · Recall@10% 22.2% · Lift@10% 2.21× · Brier 0.215 → 0.098 after calibration · no racial subgroup ROC-AUC gap > 5pp
- **Why it matters:** Patient-grouped splits (no identity leakage), risk tiers that map to a real intervention workflow, and a model card and fairness audit built in — not bolted on.

### 💊 [pharmacovigilance-nlp](https://github.com/ferozobaid/pharmacovigilance-nlp)
> *NLP pipeline classifying clinical free text as Adverse Drug Events, with biomedical NER for drugs and diseases.*
- **Stack:** scispaCy (BC5CDR), TF-IDF + Count + NER `FeatureUnion`, scikit-learn LR/NB/SVC/RF, HuggingFace `datasets`
- **Headline numbers:** F1 0.842 at the balanced threshold · 99.5% recall at the high-recall triage threshold (designed for "catch every ADE" use cases)
- **Why it matters:** Triage layer that prioritizes human reviewers — high-recall by design, because missing an ADE is far more expensive than reading a non-ADE.

### 📊 [consumer-market-insights-dashboard](https://github.com/ferozobaid/consumer-market-insights-dashboard)
> *Sanitized executive Power BI concept for monthly market reporting — KPI governance, category performance, channel mix, growth divergence.*
- **Stack:** Power BI, DAX, Power Query (M), star-schema semantic model, dataflows
- **Why it matters:** Fictional NOVARA Canada / *Northstar Insights* portfolio version of a real client-facing BI build. Shows how I design dashboards for senior leaders — one-message-per-page, governed measures, consistent period logic.

### 🎵 [Spotify-Recommendation-Model](https://github.com/ferozobaid/Spotify-Recommendation-Model)
> *Two-level K-Means + cosine-similarity recommender on 114K Spotify tracks — six mood archetypes, balanced subcluster allocation, shipped as a Gradio app.*
- **Stack:** scikit-learn (KMeans, cosine_similarity), Gradio, pandas
- **Why it matters:** Audio-feature-first recommender that complements collaborative filtering instead of competing with it. Mood as a first-class citizen, not a side label.

### 🌿 [velo-pk-chatbot-demographic-recommender](https://github.com/ferozobaid/velo-pk-chatbot-demographic-recommender)
> *Decision-tree chatbot + synthetic dataset generator to recommend optimal flavour/strength mixes for small retailers and surface under-realized flavours.*
- **Stack:** Python, decision-tree survey logic, weighted probability sampling
- **Why it matters:** Translates qualitative consumer-insight work into a scalable structured dataset — the kind of asset trade-marketing teams actually need to make assortment decisions.

---

## Technical skills

**Languages**
`Python` · `SQL` · `R` · `TypeScript` · `DAX` · `M (Power Query)`

**ML / data science**
`pandas` · `NumPy` · `scikit-learn` · `XGBoost` · `CatBoost` · `SHAP` · `CausalML` · `DoWhy` · `spaCy` / `scispaCy` · `HuggingFace datasets`

**Business intelligence**
`Power BI` · `DAX measure governance` · `Power Query` · `Star-schema modeling` · `Executive dashboard UX`

**Web / product**
`Next.js` · `React` · `Tailwind` · `REST APIs` · `Vercel` · `GitHub Actions`

**Cloud & data platforms**
`Databricks` · `Azure (fundamentals)` · `BigQuery` · basic `Snowflake`

**AI tooling**
`OpenAI API` · `Anthropic Claude API` · `LLM evaluation & caching` · `Claude Code` · `Codex` · agentic workflow design

**Domains**
Machine learning · NLP · recommendation systems · predictive modeling · causal inference · BI · executive analytics · sports analytics

---

## Currently focused on

- 🤖 **AI-powered analytics apps** — typed frontends sitting on top of offline ML, with LLMs handling explanation, not prediction
- ⚽ **Sports prediction models** — World Cup 2026 calibration work; Elo + xG + ML ensembles; tournament-level Monte Carlo
- 📊 **BI dashboards** — governed semantic models and executive-first UX for commercial reporting
- 🎯 **Recommendation systems** — mood/context-aware, audio-feature-first, explainable
- 🔁 **Agentic workflows** — building with Claude Code, Codex, and SDK-style tool-use loops

---

## Background

- 🎓 **Master of Management in Analytics**, McGill University (2026)
- 🌏 **5 years at British American Tobacco** — Trade Marketing & Commercial Analytics across APAC
- 🇨🇦 Based in Montréal · open to roles across Canada and remote

---

## Connect

- 💻 GitHub: [github.com/ferozobaid](https://github.com/ferozobaid)
- 📧 Email: [feroz.khan@mail.mcgill.ca](mailto:feroz.khan@mail.mcgill.ca)
- 💼 LinkedIn: *([feel free to link your profile here]())*

---

<p align="center">
  <em>Open to Analytics, BI, Data Science, AI Product, and Strategy Analytics roles.</em>
</p>
