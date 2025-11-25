# Assignment-4-Clustering-Analysis
Clustering Analysis – Construction Project Form Segmentation

This project uses clustering to group construction project forms based on how they behave during a project. Instead of predicting a single outcome like “open” or “closed,” the goal is to understand different types of forms and how much work they require. The dataset includes real construction project information such as form status, actions taken, comments, and project details.

Industry and Dataset

The dataset represents forms collected from construction projects. Each form captures activity such as how many actions were taken, how many items are overdue, and how much follow-up is required. These features help show how forms move through a project and how much effort they need from the team.

Project Overview

The notebook includes:

Data cleaning and preparation

A review of the original label (is_closed)

Using the elbow method and silhouette score to choose the number of clusters

Running K-means clustering on the selected features

Visualizing clusters with PCA

Comparing the clusters to the original label

Creating personas and action plans for each cluster

Summary of Findings

The clustering results identified different groups of forms that behave in unique ways. Some clusters include simple, low-effort forms, while others represent forms with more activity and higher workloads. A few clusters are linked to larger projects, and others show signs of higher risk due to the number of open or overdue actions. These patterns help show where project teams may need more support and where tasks are running smoothly. The results provide a clearer picture of how work actually moves through the construction process beyond the basic open-versus-closed status.
