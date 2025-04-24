# Hierarchical-Bayesian-Diffusion-Drift-Model-for-Working-Memory-Analysis

## Overview
This repository contains the code used to apply the Hierarchical Bayesian Diffusion Drift Model (HDDM) to analyze working memory performance. The model aims to examine the cognitive processes involved in working memory tasks, particularly focusing on reaction time and accuracy, and how they may differ across various conditions (e.g., cognitive vs. affective tasks).

## Model Description
The Hierarchical Bayesian Diffusion Drift Model (HDDM) is used for modeling decision-making processes under uncertainty. The model is based on the drift-diffusion framework, where decision-making is modeled as a noisy accumulation of evidence over time. In this application, the model is used to analyze working memory performance, considering various conditions that may affect cognitive processing.

### Key Parameters:
v (drift rate): Represents the rate of evidence accumulation.

a (boundary separation): The threshold for decision-making.

t (non-decision time): The time taken for processes other than the decision itself (e.g., encoding, response execution).

z (starting point): The initial bias towards one of the two response options.
