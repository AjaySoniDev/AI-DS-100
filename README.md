<h1 align="center">AI-DS-100</h1>

<p align="center">
  <strong>Applied AI & Data Science project lab organized as independent learning bundles.</strong><br>
  The current repository contains 78 project ZIP archives across Basic, Intermediate, and Advanced tracks, spanning tabular ML, forecasting, recommendations, NLP, computer vision, fraud/risk, explainability, and deployment-oriented exercises.
</p>

<p align="center">
  <img alt="Status" src="https://img.shields.io/badge/status-project%20lab-blue">
  <img alt="Bundles" src="https://img.shields.io/badge/project%20bundles-78-purple">
  <img alt="Basic" src="https://img.shields.io/badge/basic-29-success">
  <img alt="Intermediate" src="https://img.shields.io/badge/intermediate-27-orange">
  <img alt="Advanced" src="https://img.shields.io/badge/advanced-22-red">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-green">
</p>

<p align="center">
  <a href="#overview">Overview</a> ·
  <a href="#current-repository-inventory">Inventory</a> ·
  <a href="#project-catalog">Catalog</a> ·
  <a href="#learning-model">Learning Model</a> ·
  <a href="#reproducibility-boundary">Boundaries</a>
</p>

---

## Overview

**AI-DS-100** is a structured collection of independently packaged AI/Data Science learning projects.

The current <code>main</code> branch contains **78 ZIP project bundles**:

| Track | Current ZIP Bundles |
|---|---:|
| Basic | 29 |
| Intermediate | 27 |
| Advanced | 22 |
| **Total** | **78** |

The repository name describes a broader 100-project direction. It should not be interpreted as a claim that 100 project bundles are already committed.

The previous root README count of 26 was stale.

---

## Current Repository Inventory

~~~text
AI-DS-100/
├── DS-Project-Basic/
│   ├── 29 project ZIP bundles
│   └── README_BASIC.md
├── DS-Project-Intermediate/
│   ├── 27 project ZIP bundles
│   └── README_INTERMEDIATE.md
├── DS-Project-Advanced/
│   ├── 22 project ZIP bundles
│   └── README_ADVANCED.md
├── README.md
└── LICENSE
~~~

The level-specific README files are synchronized with the current 29 / 27 / 22 archive inventory and provide track-specific learning guidance.

---

## Project Catalog

### Basic — 29 Bundles

| # | Project |
|---:|---|
| 1 | Advertising Sales Prediction |
| 2 | Air Quality Index Basic Prediction |
| 3 | BMI Category Prediction |
| 4 | Bank Note Authentication |
| 5 | COVID-19 Basic Data Analysis |
| 6 | Calories Burned Prediction |
| 7 | Credit Card Customer Segmentation Basic |
| 8 | Customer Purchase Prediction |
| 9 | Delhi House Price Prediction |
| 10 | Employee Attrition Basic Prediction |
| 11 | Employee Salary Prediction |
| 12 | Football Player Value Prediction |
| 13 | Fruit Type Classification |
| 14 | Grocery Sales Prediction |
| 15 | IPL Match Winner Basic Prediction |
| 16 | Iris Flower Classification |
| 17 | Laptop Price Prediction |
| 18 | Loan Amount Prediction |
| 19 | Mall Customer Segmentation |
| 20 | Medical Cost Prediction |
| 21 | Mobile Price Range Classification |
| 22 | Movie Rating Prediction |
| 23 | Netflix Movies EDA |
| 24 | Pima Indians Diabetes Prediction |
| 25 | Red Wine Quality |
| 26 | SFR Analysis |
| 27 | Salary Prediction |
| 28 | Sleep Disorder Prediction |
| 29 | Titanic Survival Prediction |

### Intermediate — 27 Bundles

| # | Project |
|---:|---|
| 1 | Bank Marketing Campaign Prediction |
| 2 | Breast Cancer Prediction |
| 3 | Cardiovascular Disease Prediction |
| 4 | Credit Card Default Prediction |
| 5 | Customer Churn Prediction |
| 6 | Customer Lifetime Value Prediction |
| 7 | Customer Segmentation with K-Means |
| 8 | Diamond Price Prediction |
| 9 | E-Commerce Product Delivery Prediction |
| 10 | Energy Consumption Prediction |
| 11 | Fake News Detection |
| 12 | Flight Delay Prediction |
| 13 | Flight Fare Prediction |
| 14 | HR Employee Attrition Prediction |
| 15 | Heart Stroke Prediction |
| 16 | Hotel Reservations Cancellation Prediction |
| 17 | House Price Prediction |
| 18 | Insurance Claim Amount Prediction |
| 19 | Loan Approval Prediction |
| 20 | Market Basket Analysis |
| 21 | Movie Recommendation System |
| 22 | Osteoporosis Risk Prediction |
| 23 | Product Recommendation System Basic |
| 24 | Resume Screening System |
| 25 | Retail Sales Forecasting |
| 26 | Room Occupancy Detection |
| 27 | Telecom Customer Churn Prediction |

### Advanced — 22 Bundles

| # | Project |
|---:|---|
| 1 | Belarus Car Price Prediction |
| 2 | Brain Tumor Classification |
| 3 | Calgary Crime Data Analysis and Neural Network Model |
| 4 | Chatbot using NLP |
| 5 | Credit Card Fraud Detection |
| 6 | Crop Yield Prediction |
| 7 | Cryptocurrency Price Forecasting |
| 8 | Customer Churn Explainability with SHAP |
| 9 | Demand Forecasting with Prophet XGBoost |
| 10 | Disease Prediction Multi-Class System |
| 11 | End-to-End ML Model Deployment Project |
| 12 | Face Mask Detection |
| 13 | Hybrid Movie Recommendation System |
| 14 | Indian Used Car Price Prediction |
| 15 | Insurance Fraud Detection |
| 16 | Job Recommendation System |
| 17 | Loan Risk Scoring System |
| 18 | OCR Text Extraction System |
| 19 | Object Detection on Custom Images |
| 20 | Plant Disease Detection |
| 21 | Traffic-Flow-Prediction |
| 22 | Warranty Claims Fraud Prediction |

---

## Learning Model

The repository is designed around repeated application of common data-science patterns:

~~~text
Problem / dataset
   ↓
Data loading
   ↓
Cleaning / preprocessing
   ↓
EDA / visualization
   ↓
Feature preparation
   ↓
Modeling
   ↓
Evaluation
   ↓
Notebook / report artifact
~~~

The growing catalog extends beyond basic classification/regression into recommendation systems, NLP, computer vision, fraud/risk, forecasting, explainability, and deployment-oriented exercises.

---

## How to Use

Each project is stored as an independent ZIP archive.

A typical workflow is:

1. choose a track;
2. download/extract one project ZIP;
3. inspect the files inside the extracted bundle;
4. open its notebook/source/report;
5. install the dependencies required by that specific project;
6. reproduce the workflow before modifying or extending it.

Because project dependencies vary, there is no single environment guaranteed to reproduce all 78 bundles.

---

## Reproducibility Boundary

The repository-level source has an important review limitation: **the projects are committed primarily as ZIP archives**.

That means GitHub's normal code review/search cannot directly inspect notebook cells, datasets, environment metadata, or model outputs inside every bundle.

Accordingly, this README makes only repository-level claims that are directly verifiable:

- 78 ZIP project bundles are present;
- their filenames and track locations are known;
- three learning tracks exist;
- MIT licensing exists at repository level.

This root audit does **not** claim that every archive:

- contains the same internal file structure;
- runs in one shared environment;
- has leakage-controlled evaluation;
- has reproducible dependency locks;
- passes automated tests;
- contains a validated benchmark.

---

## Current Maturity

AI-DS-100 is best described as a **content/product learning lab** rather than a conventional software-engineering repository.

Strengths:

- broad applied-ML domain coverage;
- clear level-based organization;
- many independent practice artifacts;
- useful portfolio/learning breadth.

Engineering limitations:

- ZIP-only packaging hides source diffs;
- no repository-level shared dependency/environment contract;
- no repository-level CI;
- no uniform project quality rubric enforced in code;
- ZIP-first packaging still limits repository-level source review.

For stronger open-source review, future versions should expose notebooks/source as normal Git files and add per-project metadata plus a machine-readable catalog.

---

## License

Released under the **MIT License**. See <code>LICENSE</code>.
