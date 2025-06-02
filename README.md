# Study-of-clustering-methods-in-market-basket-analysis
Term Paper by Ivan Churilov

📁 Repository Description
This repository contains data files and the main codebase for processing intermediate results and generating final summary tables as part of a data analysis project. The project focuses on clustering, association rules, and customer segmentation using various metrics.

📂 Project Structure

.xlsx files — Excel files containing intermediate calculation results, final output tables, and matrices used for reporting or visualization.  

Clustering Results:  
8_klasters.xlsx: Contains results from clustering with 8 clusters.  
10_klasters.xlsx: Contains results from clustering with 10 clusters.  
12_klasters.xlsx: Contains results from clustering with 12 clusters.  
8_klasters_ne_summa.xlsx: Contains results from clustering with 8 clusters for each individual client.  
10_klasters_ne_summa.xlsx: Contains results from clustering with 10 clusters for each individual client.  
12_klasters_ne_summa.xlsx: Contains results from clustering with 12 clusters for each individual client.  
EM_8_klasters_ne_summa.xlsx: Clustering results using Expectation-Maximization (EM) algorithm with 8 clusters (excluding sum metrics).  
association_rules.xlsx: Contains association rules derived from the dataset.  
клиенты_c_кластерами_EM.xlsx: Customer data clustered using the EM algorithm.  

Customer Metrics Matrices:  
матрица_клиентов_c_дополнительными_MET...xlsx: Matrix of customers with additional metrics.  
матрица_клиентов_c_метриками_сумма.xlsx: Matrix of customers with summation metrics.  
матрица_клиентов_c_метриками_сумма.xlsx: Another matrix of customers with summation metrics.  
матрица_клиентов_c_регионами.xlsx: Matrix of customers grouped by regions.  
матрица_клиентов_c_средним_чеком.xlsx: Matrix of customers with average transaction amounts.  

These .xlsx files are generated at different stages of the analysis pipeline and serve as inputs or outputs for further processing.  
project.ipynb — The core Jupyter Notebook of the project. It includes the full logic for data loading, preprocessing, clustering, association rule mining, and result generation. This notebook is the primary entry point for running the analysis.  
  
💡 Purpose
The purpose of this repository is to maintain all versions of the data throughout the processing pipeline and ensure full reproducibility of the analytical workflow through a single notebook file (project.ipynb). The project aims to explore customer segmentation using clustering techniques (e.g., K-means, EM), analyze association rules, and generate detailed matrices for further insights.
