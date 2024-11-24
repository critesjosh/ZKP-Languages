# Empirical Study of Zero-Knowledge Proof (ZKP) Languages
This repository presents an empirical study of Zero-Knowledge Proof (ZKP) languages (including zkVMs), offering an overview of the most prominent ones. The study leverages the GitHub API to gather and analyse key metrics about repositories related to each language (e.g., number of stars, date of last update, etc.).

## Overview

This repository includes:

- A quantitative analysis of repositories for many ZKP languages using metrics such as:
    - Number of stars
    - Number of open issues
    - Date of last update
    - Number of contributors
- Visualizations to highlight interesting trends.
- All code used for data collection and visualization.

## Studied ZKP Languages

This study covers the following ZKP languages:

| Name          | Type       |
|---------------|------------|
| **Circom**    | HDL        |
| **ZoKrates**  | DSL        |
| **Cairo**     | DSL        |
| **Nexus VM**  | zkVM       |
| **RISC Zero** | zkVM       |
| **snarkVM**   | zkVM       |
| **SP1**       | zkVM       |

- **HDL**: Hardware Description Language, used for circuit descriptions.
- **DSL**: Domain-Specific Language, designed specifically for writing ZKP programs.
- **zkVM**: Zero-Knowledge Virtual Machine, a virtual machine designed to execute programs written in standard programming languages while generating zero-knowledge proofs of their correctness.

## Visualizations

Graphs are provided to illustrate:
- Number of repositories with more than 1 star for each language.
- Number of repositories updated after 1 January 2024 for each language.
- Number of repositories with more than 10 total issues for each language.
- Percentage of Circom VS ZoKrates programs.
- Comparison of the total number of repositories across all zkVMs VS Circom VS ZoKrates.

## Repository Structure

- **`graphs/`**  
  Contains visualizations of the study in `.png` format.
- **`metrics/`**  
  Contains `.csv` files with detailed metrics for each language and zkVM.

- **`src/`**  
  Contains source files for data collection and analysis:
  - `data_analyzer.ipynb`: Jupyter notebook for analysing and visualising data.
  - `data_collector.py`: Python script for fetching data using the GitHub API.
  - `requirements.txt`: Lists Python dependencies required for running the project.

- **`README.md`**  
  This file.

