# Saif Buheis

**ML research scientist. I build models that survive the tests built to break them.**

Applied machine learning for public-safety and epidemiological decision-making at the University of Toronto, under Dr. Jenny Cui. HBSc in Computer Science, Geospatial Data Science, and Mathematics — Class of 2026, Toronto.

Most of my work is on messy public data: epidemic forecasting, fire risk, emergency response. What I care about isn't benchmark-topping numbers — it's validation discipline. Verifying a premise before building on it, and designing evaluations that actively try to break my own claims.

---

### Research

**Physics-informed ST-GNN for COVID-19 forecasting** — graph neural network with compartmental disease mechanics embedded directly in the network, so the learned internals stay epidemiologically interpretable. Beats a persistence baseline by 5.1% MAE at two weeks and 8.8% at four, transfers zero-shot to held-out states, and independently recovers the ~48% Omicron severity drop reported in the literature.

**Toronto fire risk** — six public datasets on an H3 hex grid behind a four-rung spatio-temporal validation ladder. The finding is a measurement, not a score: roughly half the discriminable fire-severity signal exists only *after* an investigator's report, not at dispatch. My own leakage guards caught two real bugs, one of which flipped a conclusion.

**Emergency response delay prediction** — ~1.75M Toronto incidents (2012–2024), fusing incident logs, road network, weather, and area-level socio-economic data. Found silent data corruption in 36% of rows, where privacy-suppressed coordinates stored as zeros were poisoning a core feature and passing every median-based sanity check.

Two of my three main projects report **honest negatives** as the finding — one after six independent tests failed to beat a one-line baseline. Knowing when to kill a direction is the part I'd defend hardest.

---

### Selected projects

| Project | What it is | Stack |
| --- | --- | --- |
| [**Resume Roaster**](https://amicooked.ca) | RAG app giving blunt, structured resume feedback. 1,000+ resumes at a 100% success rate, engineered down to $0.011 per run. | Next.js, AWS Bedrock, Lambda, FAISS, Docker |
| **Cadillac F1 Dashboard** | Top 10% at the Global Launch Challenge. Predictive maintenance at R² = 0.91 across eight components, plus real-time brand-sentiment monitoring. | XGBoost, Flask, React, PostgreSQL |
| **Roof Damage Detection** | U-Net segmentation quantifying roof damage from drone imagery. +12% IoU from shadow/artifact preprocessing; sliding-window tiling for full-size GeoTIFFs. | PyTorch, OpenCV, GDAL, ArcGIS Pro |
| **ML-Powered Bill Categorizer** | Incremental-learning classifier that ingests user corrections in real time. 96% accuracy over 5,000+ transactions. | scikit-learn, FastAPI, Angular, PostgreSQL |

---

### Stack

**ML & data** · PyTorch · PyTorch Geometric · scikit-learn · XGBoost · LightGBM · SHAP · NumPy · Pandas · OpenCV · LangGraph

**Geospatial** · GeoPandas · OSMnx · H3 · Shapely · GDAL · ArcGIS Pro

**Systems** · Python · FastAPI · Flask · PostgreSQL · AWS (Lambda, Bedrock) · Docker · pytest · TypeScript · React · Next.js

---

### Reach me

Currently available for ML and SWE roles.

[Portfolio](https://sbprjcts.github.io/PortfolioWebsite/) · [LinkedIn](https://linkedin.com/in/saif-buheis) · [saif.buheis@gmail.com](mailto:saif.buheis@gmail.com)