# Data Science & Machine Learning Notebooks

Applied data-science and machine-learning notebooks from **TC2004B – Análisis de Ciencia de Datos** (Tecnológico de Monterrey). End-to-end work covering NLP, clustering, classification, model evaluation, imbalanced data, and generative models.

## Notebooks

| # | Notebook | What it covers |
|---|----------|----------------|
| 1 | `1_word2vec-kmeans-clustering.ipynb` | Grouping customer comments & classifying products with **Word2Vec** embeddings, **KMeans** / Agglomerative clustering, and **PCA / NMF** dimensionality reduction (incl. 3D visualization). |
| 2 | `2_knn-word2vec-classification.ipynb` | Text classification with **K-Nearest Neighbors** over Word2Vec features, with train/test evaluation. |
| 3 | `3_model-evaluation-and-hyperparameter-tuning.ipynb` | **Cross-validation**, evaluation metrics, **GridSearch** hyperparameter tuning, **RFE** feature selection and scikit-learn **pipelines** (Logistic Regression, Random Forest, KNN, XGBoost). |
| 4 | `4_imbalanced-data-balancing.ipynb` | Handling **imbalanced datasets**: resampling, **ROC curves** and confusion matrices. |
| 5 | `5_generative-recommendations-azure-openai.ipynb` | Data cleaning + **generative recommendations** using GPT-4 via **Azure OpenAI**. |

## Tech stack
Python · pandas · NumPy · scikit-learn · gensim · NLTK · XGBoost · Matplotlib · seaborn · Azure OpenAI

## Setup
```bash
pip install -r requirements.txt
```
Notebook 5 reads credentials from environment variables (no keys are stored in the code):
```bash
export AZURE_OPENAI_API_KEY="your-key"
export AZURE_OPENAI_ENDPOINT="https://your-resource.cognitiveservices.azure.com/..."
```
> Datasets are not included in this repository.

## Author
**Steffany Lara** — Data Science & Mathematics Engineering, Tecnológico de Monterrey.
