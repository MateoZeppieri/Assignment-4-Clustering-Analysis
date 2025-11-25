# Assignment-4-Clustering-Analysis
Clustering Analysis – Construction Project Form Segmentation

This project applies unsupervised learning to segment construction project forms into meaningful groups based on activity levels, workload patterns, and project characteristics. The analysis uses the Construction and Project Management Example Data and focuses on identifying operational differences that are not captured by the original closure label.

Industry and Dataset

The dataset represents real construction project forms, including information on status, actions, comments, documentation, and project identifiers. Each record reflects a single form within a project workflow. The features used for clustering include numeric indicators such as open actions, total actions, and activity levels. The goal is to understand how different types of forms behave across projects.

Project Overview

This notebook performs:

Data preparation, cleaning, and standardization

Review of the original supervised label (is_closed)

Elbow method and silhouette analysis to select the number of clusters

K-means clustering using the chosen K

PCA visualization of cluster structure

Comparison of clusters to the original label

Creation of personas and action plans for each segment

Summary of Findings

The clustering results revealed distinct groups of forms that differ in workload, complexity, and project scale. Some clusters reflect routine, low-activity forms, while others show signs of higher workload or greater risk. These differences provide insights that go beyond the open-versus-closed label and highlight where teams may need support or where processes are already efficient.
