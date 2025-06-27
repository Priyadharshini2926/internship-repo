# internship-repo
🔍 What is OCR?
OCR (Optical Character Recognition) is a technology used to extract text from scanned documents, images, or PDFs and convert them into editable/searchable text.

🧠 OCR Working Process
Image Preprocessing – noise removal, grayscale, deskewing, contrast.

Text Detection – locating text regions.

Character Recognition – recognizing characters/words.

Post-processing – correcting recognition errors using dictionaries/language models.

⚠️ OCR Challenges
Blurred or low-quality images

Handwriting recognition

Mathematical symbols

Mixed content (text + diagrams)

Complex layouts

📝 Types of Answer Sheets Explored
Theory-Based – paragraph-style handwritten answers.

Mathematical – equations, symbols (∫, π), derivations.

Diagram-Based – biology, circuits, labeled figures.

Mixed Content – combinations of text, math, and diagrams.

🧪 Tools and Solutions
Tesseract OCR, Google Cloud Vision, Microsoft Azure OCR

For Math: MathPix, InftyReader

For diagrams: Combine OpenCV + Tesseract

For complex layouts: LayoutParser, Detectron2, DocTR
🔹 What is Git?
Git is a Distributed Version Control System (DVCS) used to track changes in source code. It allows multiple developers to collaborate without overwriting each other's work.

✅ Git Features
Distributed architecture

SHA-1 data integrity

Fast branching & merging

Local commit history

Collaborative development support

🔧 Common Git Commands
# Configuration
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

# Repo Setup
git init
git clone <repo_url>

# Staging & Committing
git add .
git commit -m "Message"

# Branching
git branch
git checkout <branch_name>
git merge <branch_name>

# Syncing
git push origin <branch>
git pull

# Logs and Undo
git log
git reset <file>
🔹 What is GitHub?
GitHub is a web-based platform built on top of Git. It allows code hosting, collaboration, and project management with features like Pull Requests, Issues, and Actions (CI/CD).

🔑 Key GitHub Concepts
Term	Description
Repo	Project folder with code
Fork	Personal copy of a repo
Pull Request	Propose changes
Issue	Bug/task tracking
README	Introductory markdown file
 Chapter 1: Introduction
📌 Overview:
This chapter sets the foundation for understanding machine learning (ML) by explaining its motivation, tools, and how to begin your journey using Python and essential libraries. A hands-on classification example is introduced using the Iris dataset.

🧠 Key Concepts:
Why Machine Learning?

Real-world problems ML can solve

Importance of understanding the task and data

Why Python for ML?

Popularity and ecosystem

Introduction to scikit-learn and installation

Essential Libraries and Tools:

Jupyter Notebook for coding interactively

Core libraries: NumPy, SciPy, matplotlib, pandas, mglearn

Python 2 vs Python 3:

Version discussion and the version used in this book

First ML Application: Iris Classification

Overview of the Iris dataset

How to split data into training and testing sets

Visualizing and understanding the dataset

Building and training a k-Nearest Neighbors (k-NN) model

Making predictions and evaluating accuracy
Supervised Learning
📌 Overview:
This chapter introduces Supervised Learning, a core concept in machine learning where models are trained using labeled data. It discusses classification and regression problems and explores various algorithms and techniques to build predictive models.

🧠 Key Concepts Covered:
Classification and Regression
Understand the difference between predicting categorical labels (classification) and continuous values (regression).

Model Evaluation Issues:

Overfitting, underfitting, generalization

How model complexity and dataset size impact performance

Popular Supervised Algorithms:

k-Nearest Neighbors (k-NN)

Linear Models (e.g., linear regression, logistic regression)

Naive Bayes Classifiers

Decision Trees and Ensemble Methods (e.g., Random Forests)

Kernelized Support Vector Machines (SVM)

Neural Networks (Introduction to Deep Learning)

Uncertainty in Predictions:

Decision function, probability estimates

Multiclass classification uncertainty handling


 Unsupervised Learning and Preprocessing
📌 Overview:
This chapter dives into learning from unlabeled data (unsupervised learning) and emphasizes the importance of data preprocessing before applying machine learning models.

🧠 Key Concepts Covered:
Types of Unsupervised Learning:
Clustering, dimensionality reduction, and feature extraction

Challenges:
Difficulties in unsupervised learning due to lack of ground truth

Preprocessing Techniques:

Scaling data (standardization, normalization)

Transforming features

Ensuring consistent preprocessing between training and test sets

Dimensionality Reduction & Feature Learning:

PCA (Principal Component Analysis)

NMF (Non-Negative Matrix Factorization)

t-SNE (t-distributed Stochastic Neighbor Embedding)

Clustering Algorithms:

k-Means Clustering

Agglomerative Clustering

DBSCAN

Evaluation and comparison of clustering methods

