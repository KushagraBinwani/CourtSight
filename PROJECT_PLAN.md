# CourtSight

## Overview

CourtSight is an AI-powered court intelligence platform designed to transform unstructured Indian legal documents into structured, searchable, and analyzable data.

The project aims to combine NLP, Information Retrieval, Unsupervised Learning, and Reinforcement Learning to uncover patterns in Indian legal cases and build tools for legal research and court analytics.

Dataset:
- OpenNyaya - Indian Supreme Court Judgments (1950-2023)
- 33,000+ OCR-cleaned judgments
- English language
- Markdown text format

---

# Project Goals

## Short-Term Goals

- Understand the structure of Indian Supreme Court judgments
- Extract useful metadata
- Generate semantic embeddings for cases
- Build a similar-case retrieval system

## Long-Term Goals

- Cluster legal cases into meaningful groups
- Detect anomalous or unusual cases
- Build legal intelligence dashboards
- Develop an RL-based court scheduling simulator

---

# Development Roadmap

## Phase 1 - Dataset Exploration

Goal:
Understand the dataset and identify useful metadata.

Tasks:
- Explore document structure
- Identify common sections
- Extract metadata candidates
- Build EDA notebook

Deliverable:
Dataset exploration report.

Status:
Not Started

---

## Phase 2 - Metadata Extraction

Goal:
Convert judgments into structured records.

Potential Fields:
- Case Name
- Date
- Judges
- Petitioner
- Respondent
- Legal Sections
- Summary

Deliverable:
Structured dataset.

Status:
Not Started

---

## Phase 3 - Embedding Generation

Goal:
Represent legal cases as vectors.

Technologies:
- Sentence Transformers
- BERT Embeddings

Deliverable:
Embeddings for all processed judgments.

Status:
Not Started

---

## Phase 4 - Similar Case Retrieval

Goal:
Find semantically similar cases.

Pipeline:

Case
↓
Embedding
↓
FAISS
↓
Top Similar Cases

Deliverable:
Search and retrieval system.

Status:
Not Started

---

## Phase 5 - Case Clustering

Goal:
Discover hidden legal categories.

Algorithms:
- KMeans
- DBSCAN
- HDBSCAN

Deliverable:
Cluster analysis report.

Status:
Not Started

---

## Phase 6 - Anomaly Detection

Goal:
Identify unusual legal cases.

Algorithms:
- Isolation Forest
- Local Outlier Factor

Deliverable:
Anomaly detection report.

Status:
Not Started

---

## Phase 7 - Court Intelligence Dashboard

Goal:
Visualize retrieval and clustering results.

Features:
- Similar Cases
- Cluster Explorer
- Anomaly Explorer

Status:
Not Started

---

## Phase 8 - Reinforcement Learning Court Scheduler

Goal:
Simulate and optimize court scheduling.

State:
- Pending Cases
- Court Backlog
- Judge Workload

Actions:
- Schedule Case
- Assign Judge

Reward:
- Reduced Backlog
- Reduced Waiting Time

Technologies:
- Gymnasium
- Stable Baselines3

Status:
Not Started

---

# Repository Structure

CourtSight/
│
├── data/
├── notebooks/
├── src/
├── reports/
├── figures/
├── app/
│
├── README.md
├── PROJECT_PLAN.md
├── requirements.txt
└── .gitignore

---

# Current Focus

Current Phase:
Phase 1 - Dataset Exploration

Immediate Next Step:
Download sample judgments and analyze document structure.
