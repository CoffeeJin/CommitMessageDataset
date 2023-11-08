# GitHub Vulnerability Commits Dataset

This repository contains a specialized dataset for training machine learning models on natural language processing (NLP) tasks, specifically to identify commits that address code vulnerabilities. It consists of two distinct sets of commits labeled as 'positive' or 'negative' based on their association with vulnerability fixes.

## About the Dataset

The dataset is constructed using commits from the GitHub Repository Database and contributions from various open-source projects on GitHub. It aims to facilitate the development of algorithms that can effectively discern and highlight commits pertinent to software security improvements.

### Dataset Composition

- **Positive Commits:** These are commits that include modifications aimed at fixing vulnerabilities. The total number of positive commits in this dataset is 6,054.
- **Negative Commits:** These commits do not pertain to vulnerability resolution and serve as counter-examples in training scenarios. The dataset includes 6,308 negative commits.

Each entry in the dataset is made up of the following information:

- **Commit (Column 1):** A unique identifier for the commit, which can be used to trace the change in the respective GitHub repository.
- **Score (Column 2):** A binary score where '1' stands for a positive commit (vulnerability-related) and '0' signifies a negative commit (non-vulnerability-related).

### File Format

The dataset is stored in comma-separated values (CSV) file format with the following structure:

commit,score
improve Document Types. ,1
Disable cache for auto responder. Fixes cronjob issue,0