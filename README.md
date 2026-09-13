# 🤖 AI/ML Foundations Cohort — Complete Teaching Repository

> A structured, hands-on Machine Learning curriculum built for absolute beginners  
> and progressively taken to an intermediate practitioner level.  
> Every notebook is self-contained, interactive, and designed to be run in Google Colab or Jupyter.

---

## 📌 About This Repository

This repository contains the complete set of teaching materials developed for an **AI/ML Foundations Cohort** — a structured learning programme designed to take students from zero prior knowledge in Machine Learning all the way to building, evaluating, and deploying real-world models.

The curriculum was designed by a practising ML/AI Engineer with the goal of making the field genuinely accessible — not by oversimplifying it, but by teaching it in the right order, with the right depth, and always grounded in real code and real data.

Every session combines:
- 📖 **Markdown teaching cells** — theory, intuition, and context explained clearly
- ▶️ **Runnable code cells** — live demonstrations of every concept
- ✏️ **Practice challenges** — YOUR TURN cells where students write their own code
- ⏱️ **Mini tasks** — timed in-class exercises to consolidate understanding
- 🚀 **Projects and capstones** — end-to-end tasks that produce real deliverables

---

## 🗂️ Repository Structure

```
ai-ml-foundations-cohort/
│
├── 📁 01_foundations/
│   └── Introduction_to_Machine_Learning.ipynb
│
├── 📁 02_python/
│   └── Meeting2_Python_for_ML.ipynb
│
├── 📁 03_data/
│   └── Meeting3_Data_is_Everything.ipynb
│
├── 📁 04_math_and_supervised_ml/
│   ├── Meeting4_5_Math_and_Supervised_ML.ipynb
│   └── Math_Deep_Dive.ipynb
│
├── 📁 05_classical_ml/
│   ├── Meeting6_Classical_ML_II.ipynb
│   └── Meeting7_Unsupervised_Learning.ipynb
│
├── 📁 06_case_studies/
│   ├── Movie_Cost_Regression.ipynb
│   └── Titanic_Survival_Classification.ipynb
│
├── 📁 07_neural_networks/
│   └── Neural_Networks_Beginner_to_Intermediate.ipynb
│
├── 📁 08_capstone/
│   └── Capstone2_House_Price_and_Recommender.ipynb
│
├── README.md
└── requirements.txt
```

---

## 📚 Notebook Descriptions

---

### 📗 01 — Introduction to Machine Learning
**`Introduction_to_Machine_Learning.ipynb`**

The definitive starting point for the entire cohort. This notebook gives students their first complete, end-to-end view of what Machine Learning actually is and how it works in practice — before any specialised topic is introduced.

**What it covers:**
- What Machine Learning is and how it differs from traditional programming
- The three paradigms: Supervised, Unsupervised, and Reinforcement Learning
- The complete ML workflow: problem definition → data → preprocessing → modelling → evaluation → deployment
- Types of ML problems: regression, classification, clustering
- How to think like an ML practitioner — framing problems in terms of data and prediction
- An introduction to key evaluation metrics: accuracy, precision, recall, F1, MAE, RMSE, R²
- A first look at the scikit-learn API
- An end-to-end walkthrough: loading data, training a model, and evaluating it — start to finish

**Intended for:** Complete beginners. No prior ML knowledge assumed.  
**Outcome:** Students leave with a clear mental model of the full ML lifecycle and have run their first working model.

---

### 📗 02 — Python for Machine Learning
**`Meeting2_Python_for_ML.ipynb`**

A focused, practical Python session designed specifically for ML work. This is not a general Python course — it covers the specific subset of Python that a practising ML engineer uses daily, with every example drawn from realistic ML scenarios.

**What it covers:**
- Variables, data types, and type conversion — with ML context
- Operators, conditionals, and control flow — writing model evaluation logic
- Loops — processing datasets, iterating over features, list comprehensions
- Functions — writing reusable ML utilities including accuracy, precision, and recall from scratch
- Data structures — lists, dictionaries, tuples, and sets applied to ML workflows
- File handling — reading and writing CSV files, managing datasets
- NumPy — array operations, vectorisation, indexing, boolean masking, statistical functions
- Pandas — DataFrames, selection, filtering, groupby, and feature engineering basics
- A mini-project: end-to-end data exploration on a real dataset

**Intended for:** Students with no coding experience.  
**Outcome:** Students can read and write Python for data manipulation and model building.

---

### 📗 03 — Data is Everything
**`Meeting3_Data_is_Everything.ipynb`**

The data preparation session — arguably the most important in the entire programme. This notebook teaches students that over 75% of ML work happens before a single model is trained, and gives them the full toolkit to handle real-world messy data.

**What it covers:**
- Types of data: structured vs unstructured, variable types (continuous, ordinal, nominal, binary)
- The complete EDA framework: schema audit, target analysis, distributions, correlations, categorical profiles
- Missing value detection and five treatment strategies including group-wise imputation
- The flag-before-impute professional pattern
- Outlier detection using IQR, Z-score, and domain rules
- Outlier treatment: dropping, capping (winsorisation), and flagging
- Feature engineering: binning, ratio features, interaction features, log transformation, encoding
- Min-Max vs Standard scaling — when to use which
- Visualisation with Matplotlib and Seaborn: histograms, box plots, bar charts, heatmaps, violin plots
- A reusable EDA pipeline function that works on any tabular dataset
- Three in-class mini tasks and a full take-home assignment

**Intended for:** Students who have completed the Python session.  
**Outcome:** Students can take any raw dataset and produce a clean, well-understood, model-ready version.

---

### 📗 04 — Math Essentials + Supervised ML I
**`Meeting4_5_Math_and_Supervised_ML.ipynb`**

A combined session that first builds the mathematical intuition needed to understand ML algorithms, then immediately applies it to the most important class of algorithms: supervised learning.

**What it covers:**

*Math (concise, intuition-first):*
- Vectors as data points, the weighted sum as a prediction
- The dot product and what it means geometrically
- Statistics essentials: mean, standard deviation, correlation, probability
- Loss functions and the concept of optimisation
- The loss curve visualised

*Supervised ML:*
- Regression vs classification — when to use each
- Linear Regression — training, evaluating with MAE and R², visualising predictions
- Logistic Regression — the sigmoid function, probability outputs, confusion matrix
- Decision Trees — how they split data, max depth, visualising the tree
- Random Forests — ensemble learning, feature importance, why they outperform single trees
- Evaluation metrics: accuracy, precision, recall, F1 score
- A mini task and a full mini-project comparing all three models on a loan approval dataset

**Intended for:** Students who have completed the data session.  
**Outcome:** Students have trained, evaluated, and compared their first real ML models.

---

### 📗 05 — Mathematics for ML: A Deep Dive
**`Math_Deep_Dive.ipynb`**

For students who want to genuinely understand what happens inside ML models — not just call functions. This notebook goes deep into the mathematics that underpins all of modern ML, presented with code, visualisations, and implementation from scratch.

**What it covers:**
- Vectors and their geometric meaning — addition, scaling, magnitude, normalisation
- The dot product — what it measures, its relationship to angle, why it drives every prediction
- Matrix multiplication — shape rules, batched operations, the neural network layer as a matrix op
- Probability distributions — Normal, Binomial, Bernoulli, Exponential, Log-Normal, Uniform — all visualised
- Bayes Theorem — derived, explained, and applied to a medical test scenario
- The Central Limit Theorem — why Gaussian noise appears everywhere in ML
- Loss functions — MSE, MAE, Huber, Binary Cross-Entropy, Categorical Cross-Entropy — all coded and plotted
- Why MSE amplifies outliers and when to prefer MAE or Huber
- The sigmoid function and the log-loss curve
- Gradient Descent — coded from scratch, visualised on a loss surface
- The effect of learning rate: too small, too large, just right — all three shown
- Linear regression trained entirely via gradient descent from raw NumPy
- The chain rule of calculus — explained through a worked example
- Backpropagation — implemented manually through a 2-layer network
- Activation functions and their gradients — Sigmoid, Tanh, ReLU, Leaky ReLU — all plotted
- A full XOR network trained from scratch verified against PyTorch autograd

**Intended for:** Intermediate students ready to go beyond the API.  
**Outcome:** Students understand what `.fit()` and `.backward()` are actually doing.

---

### 📗 06 — Classical ML II: Going Deeper
**`Meeting6_Classical_ML_II.ipynb`**

A deep treatment of three more powerful classical algorithms, followed by the most important conceptual framework in all of ML: understanding and preventing overfitting.

**What it covers:**
- K-Nearest Neighbours — internal distance computation shown step by step, K selection curve, silhouette scoring, distance metric comparison (Euclidean vs Manhattan)
- Naive Bayes — GaussianNB on tabular data, MultinomialNB on text, a working spam classifier
- Support Vector Machines — the maximum margin concept, the kernel trick, decision boundaries visualised for linear and RBF kernels, C and gamma hyperparameter effects
- Overfitting vs underfitting — the bias-variance tradeoff, polynomial degree visualisation
- L1 (Lasso) and L2 (Ridge) regularisation — weight sparsity shown, comparison visualised
- Cross-validation — stratified K-fold, learning curves for diagnosing data hunger
- GridSearchCV and RandomizedSearchCV — professional hyperparameter tuning
- Scikit-learn Pipelines — data leakage explained, ColumnTransformer for mixed data types, save/reload with joblib
- Two mini tasks and a full pipeline project

**Intended for:** Students who have completed the supervised ML sessions.  
**Outcome:** Students build professional, leakage-free, tuned ML pipelines.

---

### 📗 07 — Unsupervised Learning
**`Meeting7_Unsupervised_Learning.ipynb`**

The complete unsupervised learning toolkit — finding patterns in data that has no labels. Grounded in a realistic customer segmentation scenario throughout.

**What it covers:**
- What unsupervised learning is and the three core tasks: clustering, dimensionality reduction, anomaly detection
- K-Means — the algorithm animated step by step, inertia, elbow method, silhouette scores, per-sample silhouette plot
- DBSCAN — density-based clustering, core/border/noise points, comparison to K-Means on non-spherical data
- Hierarchical clustering — Ward, complete, and average linkage, dendrogram reading and tree cutting
- Cluster profiling — z-score heatmaps, radar charts, business segment naming
- PCA — scree plot, loadings heatmap, explained variance, 2D and 3D visualisation
- t-SNE — perplexity effects at four settings, PCA→t-SNE professional pipeline on handwritten digits
- Anomaly detection — Isolation Forest, Local Outlier Factor, and One-Class SVM compared side by side
- Anomaly score distributions and threshold visualisation
- Two mini tasks and a full unsupervised pipeline project

**Intended for:** Students who have completed the supervised ML sessions.  
**Outcome:** Students can segment customers, detect anomalies, and visualise complex data.

---

### 📗 08 — Movie Cost Regression: A Case Study
**`Movie_Cost_Regression.ipynb`**

The first of two applied case studies. This notebook takes students through the complete ML workflow on a real, engaging dataset — predicting movie production costs from film metadata. It is designed to show students, concretely and end-to-end, exactly what a real ML project looks like from data import to model testing.

**What it covers:**
- Loading and inspecting a real movie dataset
- Exploratory data analysis specific to the domain
- Feature engineering from movie metadata (genre, runtime, release year, ratings, studio)
- Handling skewed distributions and outlier budgets
- Building and comparing multiple regression models
- Interpreting model coefficients in the context of the film industry
- Evaluating with MAE, RMSE, and R²
- Analysing residuals — which movies does the model get wrong and why?
- Student practice cells throughout the workflow

**Intended for:** Students who have completed the data and supervised ML sessions.  
**Outcome:** Students have completed a full regression project on a real dataset with domain interpretation.

---

### 📗 09 — Titanic Survival Classification: A Case Study
**`Titanic_Survival_Classification.ipynb`**

The second applied case study and one of the most famous datasets in all of ML. This notebook walks students through a classification problem from raw data to a working model, with particular attention to the thinking process behind each decision.

**What it covers:**
- Loading and exploring the Titanic dataset
- Understanding the target: binary survival prediction
- Domain-informed feature engineering (title extraction from names, family size, fare per person, deck)
- Handling the specific missing value patterns of this dataset (Age, Cabin, Embarked)
- Encoding categorical features: Sex, Embarked, Title, Pclass
- Training and comparing Logistic Regression, Decision Tree, and Random Forest classifiers
- Evaluating with accuracy, precision, recall, F1, and ROC-AUC
- Visualising a confusion matrix and ROC curve
- Feature importance analysis — which passenger characteristics mattered most?
- Submission-ready predictions

**Intended for:** Students who have completed the data and supervised ML sessions.  
**Outcome:** Students can apply the full classification workflow to a real historical dataset and interpret the results meaningfully.

---

### 📗 10 — Neural Networks: Beginner to Intermediate
**`Neural_Networks_Beginner_to_Intermediate.ipynb`**

The deepest and most extensive notebook in the cohort. Takes students from the single perceptron all the way to convolutional networks and transfer learning, using PyTorch as the primary framework with TensorFlow/Keras also covered.

**What it covers:**
- The biological neuron and its mathematical abstraction — the perceptron
- Why XOR requires depth — the fundamental motivation for multi-layer networks
- Building networks in PyTorch: `nn.Module`, `nn.Sequential`, Functional API
- Three architectures compared: Shallow, Medium, and Deep with residual connections
- The full production training loop: DataLoader, AdamW, cosine annealing scheduler, gradient clipping, early stopping, and model checkpointing
- Dropout — behaviour in train vs eval mode, effect of dropout rate on overfitting
- Batch Normalisation — training stability visualised with and without BN
- Convolutional Neural Networks — Conv2d, MaxPool, BatchNorm2d, the full CNN on MNIST
- Transfer Learning with ResNet18 — feature extraction vs progressive unfreezing
- TensorFlow/Keras — Functional API, compile, callbacks (EarlyStopping, ReduceLROnPlateau, ModelCheckpoint)
- Advanced practice: multi-class classification, Focal Loss implementation, model weight analysis
- Capstone 1 suggestion: Retinal disease detection from fundus images (APTOS 2019 dataset)

**Intended for:** Students who have completed the supervised ML and math sessions.  
**Outcome:** Students build, train, and evaluate deep neural networks in both PyTorch and Keras.

---

### 📗 11 — Capstone 2: House Price Prediction & Recommender System
**`Capstone2_House_Price_and_Recommender.ipynb`**

The final capstone project guide. This is a project brief and architectural walkthrough — not a tutorial. Students source their own data, make their own modelling decisions, and ship a live deployed web application.

**What it covers:**
- The real-world problem: fair property pricing and intelligent recommendation
- Dataset sourcing guidance — public datasets and African real estate portals
- A complete EDA scaffold and cleaning checklist
- Feature engineering recommendations specific to housing data
- A preprocessing pipeline scaffold with ColumnTransformer
- Model comparison guide: Linear Regression through XGBoost — students choose and justify
- Residual analysis scaffold — understanding where the model fails
- The `HouseRecommender` class — content-based similarity search with KNN
- A full Streamlit app scaffold (`app.py`) with sidebar inputs, price display, feature importance chart, and expandable recommendation cards
- Step-by-step deployment guide to Streamlit Community Cloud (free, public URL)
- A 100-mark evaluation rubric and 17-item submission checklist

**Intended for:** Students who have completed the full programme.  
**Outcome:** A deployed, publicly accessible ML web application in the student's portfolio.

---

## 🚀 Getting Started

### Run in Google Colab (Recommended — No Setup Required)

Click any notebook file in this repository, then click the **"Open in Colab"** badge or navigate to:

```
https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/path/to/notebook.ipynb
```

Google Colab provides free GPU access, all major libraries pre-installed, and runs entirely in your browser.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

---

## 📦 Requirements

```
numpy>=1.24
pandas>=2.0
matplotlib>=3.7
seaborn>=0.12
scikit-learn>=1.3
scipy>=1.10
joblib>=1.3
torch>=2.0
torchvision>=0.15
tensorflow>=2.13
xgboost>=2.0
lightgbm>=4.0
streamlit>=1.28
plotly>=5.0
```

Install all at once:
```bash
pip install -r requirements.txt
```

> **Note:** PyTorch and TensorFlow can be large downloads. For GPU-accelerated training, use Google Colab or a machine with a CUDA-capable GPU.

---

## 🎯 Who This Is For

| Learner Profile | Starting Point |
|----------------|----------------|
| Complete beginner — no Python, no ML | Start at Notebook 01 |
| Knows Python, new to ML | Start at Notebook 01 or 03 |
| Knows ML basics, wants to go deeper | Start at Notebook 05 or 06 |
| Wants to learn neural networks | Go directly to Notebook 10 |
| Ready for a capstone project | Notebooks 08 (Capstone 1) or 11 (Capstone 2) |

---

## 📋 Recommended Learning Order

```
01  Introduction to ML          ← Start here
     ↓
02  Python for ML               ← If new to Python
     ↓
03  Data is Everything          ← Critical — don't skip
     ↓
04  Math + Supervised ML I      ← First models
     ↓
05  Math Deep Dive              ← Optional but powerful
     ↓
06  Classical ML II             ← More algorithms + tuning
     ↓
07  Unsupervised Learning       ← Patterns without labels
     ↓
08  Movie Cost Regression       ← Case study: regression
     ↓
09  Titanic Classification      ← Case study: classification
     ↓
10  Neural Networks             ← Deep learning
     ↓
11  Capstone: House Predictor   ← Build and ship something real
```

---

## 🛠️ Teaching Approach

Every notebook in this repository follows the same teaching philosophy:

**Theory before code, intuition before formula.**  
Every concept is explained in plain language before any mathematics or code is introduced. Formulas appear after the intuition has been built — not before.

**Real data, real problems.**  
Synthetic toy datasets are used only when necessary to illustrate a concept cleanly. Every session uses or references real-world data and real problem framings.

**You learn by doing.**  
Each notebook contains multiple `✏️ YOUR TURN` cells — challenges where students write their own code, not copy-paste from examples. The notebooks are designed to be worked through, not just read.

**Nothing is a black box.**  
Wherever possible, algorithms are implemented from scratch before being demonstrated using a library. Students who complete this programme understand what the library is doing, not just how to call it.

---

## 📊 Programme Statistics

| Metric | Value |
|--------|-------|
| Total notebooks | 11 |
| Estimated total learning hours | 25 – 35 hours |
| Lines of teaching code | 3,000+ |
| Algorithms covered | 20+ |
| Datasets used | 10+ |
| Frameworks taught | Python, NumPy, Pandas, Scikit-learn, PyTorch, TensorFlow/Keras, Streamlit |

---

## 🤝 Contributing

This is a living curriculum. If you are a student who completed the programme and found an error, have a suggestion, or want to contribute an improved practice exercise:

1. Fork the repository
2. Create a branch: `git checkout -b fix/your-fix-name`
3. Make your changes
4. Submit a pull request with a clear description

---

## 📄 Licence

This repository is released for educational use. You are free to use, adapt, and share these materials for non-commercial teaching purposes with appropriate attribution.

---

## 👤 Author

Developed and maintained by an AI/ML Engineer with experience building production ML systems across fintech, healthtech, and data analytics. This curriculum was designed to make high-quality ML education accessible to practitioners in emerging markets.

---

<div align="center">

**If this repository helped you, please give it a ⭐ — it helps others find it.**

*Built with the belief that the next generation of great ML engineers will come from everywhere.*

</div>
