**Auto Model Recommender**
This Python script analyzes your dataset and automatically suggests the most suitable Machine Learning or Deep Learning model family to achieve the best performance.

It works by:

* Automatically detecting whether your problem is **classification** or **regression**.
* Comparing **linear** and **non-linear** models using cross-validation.
* Determining whether your data is predominantly linear or non-linear, and explaining **why**.
* Recommending the best model family based on both performance and data characteristics.

**Outputs:**

* `model_recommendation_report.txt` — a human-readable report summarizing results, evidence, and recommendations.
* `model_recommendation_suggestions.json` — a structured JSON file containing the recommended model family, evaluation scores, and linearity assessment.

All console messages and reports are generated in **English**.
