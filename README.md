# Hi, I'm Vladislav

ML engineer & data analyst with focus on machine learning — tabular forecasting, computer vision, NLP / LLM-based pipelines, and product analytics.

M.Sc. student in Applied Mathematics & Informatics at HSE University (Moscow), with a CV & ML exchange semester at CUHK-Shenzhen. Based in Saint Petersburg, shipping projects across the stack.

---

## Featured projects

### Machine learning

**[retail-sales-prediction](https://github.com/Vladislavbro/retail-sales-prediction)** — sneaker daily-sales forecasting.
CatBoost with weighted MAE, 8 blocks of engineered features (price, promo, inventory, lags, elasticity, interactions), explicit leakage-prevention via masked time series, Optuna hyperparameter search, MLflow tracking in Docker. **Weighted MAE: 3.10 baseline → 2.45 final.**

**[Spotter](https://github.com/Vladislavbro/Spotter)** — Wildberries marketplace analytics. Daily scraper, NLP pipeline for Russian product titles (`pymystem3` lemmatisation, spaCy dependency parsing for root-noun + adjective features), per-category KMeans clustering on spaCy embeddings, MongoDB store, Telegram bot, web UI, PM2 deploy. Live at [spotter.fun](https://spotter.fun).

### Computer vision

**[tooth_recognition](https://github.com/Vladislavbro/tooth_recognition)** — multi-class tooth segmentation with **nnU-Net v2** (CUHK CV course). Custom dataset converter, mask cleaning utilities, 5-fold k-fold training on A100, automated `nnUNetv2_find_best_configuration` + inference pipeline.

**[3d-sneaker](https://github.com/Vladislavbro/3d-sneaker)** — 3D object reconstruction with **3D Gaussian Splatting + SegAnyGaussians**. SAM-based background pre-processing, COLMAP for camera poses, CLIP/SAM feature extraction. Final model: ~280 MB / 70k Gaussians / 90 FPS at 1080p.

**[CV-nuScenes](https://github.com/Vladislavbro/CV-nuScenes)** — Bird's-Eye View perception on nuScenes. Camera-only vs camera+radar Simple-BEV comparison under clean / dark / camera-failure scenarios, plus distance-aware confidence thresholding. Camera+radar lifts Mean IoU from 33.57 → 44.60 in low-light. Co-authored with [@JussiMiettinennn](https://github.com/JussiMiettinennn).

### NLP / LLM

**[llm_vs_ner_wikiann-ru](https://github.com/Vladislavbro/llm_vs_ner_wikiann-ru)** — prompt-engineering study for Russian NER on WikiANN with Gemini. Systematic sweep over shot count, hard examples, prompt style, model variant, and self-verification. **Best F1 = 0.89** (10-shot + difficult examples), versus 0.38 zero-shot baseline.

### Product / data analytics

**[retail-analysis](https://github.com/Vladislavbro/retail-analysis)** — e-commerce funnel and product analytics on event-level data (`view` / `cart` / `purchase`). Funnel breakdowns by hour and user type, AOV / AIV / time-to-purchase / abandoned-cart metrics, three identified friction points and five data-driven growth hypotheses.

---

## Team / research projects

**[Sen2Fire-Wildfire-Detection](https://github.com/TitoNicolaDrugman/Sen2Fire-Wildfire-Detection)** — wildfire detection on Sentinel-2 satellite imagery. Benchmark of nnU-Net, SegFormer and Dual-Stream architectures with Test-Time Augmentation and spatial weighting. **Achieved SOTA on Sen2Fire (F1 = 0.3675).** Team project at CUHK; my contributions are visible in the repo's contributors graph.

---

## Stack

**ML / DL:** Python · PyTorch · CatBoost · scikit-learn · Optuna · MLflow · nnU-Net v2 · 3D Gaussian Splatting · SAM · CLIP
**NLP:** spaCy · pymystem3 · NLTK · LLM APIs (Gemini, Gemma family)
**Data:** pandas · NumPy · Plotly · Jupyter
**Infra:** Docker · MongoDB · Git · PM2 · Google Colab / A100

---

## Education

- **HSE University, Moscow** — M.Sc. in Applied Mathematics & Informatics (2024 – 2026)
- **CUHK-Shenzhen** — exchange semester, Computer Vision & Data Analysis (Aug – Dec 2025)

---

## Connect

- Email: [i.vladsn@gmail.com](mailto:i.vladsn@gmail.com)
- Telegram: [@nemasterr](https://t.me/nemasterr)
- GitHub: [@Vladislavbro](https://github.com/Vladislavbro)
