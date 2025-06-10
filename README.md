# RL-Benchmarking
CS224R Project

Project Overview

This repository contains the code and analyses for evaluating offline reinforcement learning (RL) algorithms on two real‐world clinical cohorts - MIMIC IV and STARR_OMOP. We compare three methods—Behavior Cloning (BC), Fitted Q-Iteration (FQI), and Conservative Q-Learning (CQL)—to understand how algorithm choice and dataset differences affect dosing policies.

Repository Structure
- mimic_potassium_repletion.ipynb     # MIMIC-IV analysis & modeling
- starr_potassium_repletion.ipynb     # STARR-OMOP analysis & modeling
- README.md                           # This file

Data Access

- MIMIC-IV: Contains PHI; pre-downloaded to a secure local environment. Not in this repo.
- STARR-OMOP: Queried via lab PI’s BigQuery project over VPN. Raw data cannot be shared here; query code is in the notebooks.
