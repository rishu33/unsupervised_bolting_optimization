# Smart Service for Quality Assessment of Bolting Processes

This repository contains the description of a research project aimed at improving quality assessment in production processes. The study focused on analyzing and classifying bolting cases using advanced data processing techniques and machine learning methods. The project integrates concepts from Auto Encoders, unsupervised learning, time series analysis, and clustering algorithms to enhance production quality.

## Project Description

Bolted connections play a pivotal role in the production industry, uniting various parts and contributing to joint integrity and overall safety. While torque value remains one of the primary metrics for assessing the effectiveness of a bolted connection, it is equally crucial to scrutinize the evolving torque patterns over time. This study examines torque patterns during the bolt-tightening process, aiming to categorize them and identify trends that enhance successful bolting.

I analyzed torque vs. time data from more than 40,000 bolting cases  and explored various methods, including Autoencoders, Dynamic Time Warping (DTW), and DBSCAN (Density-Based Spatial Clustering of Applications with Noise). Further, I developed custom functions to improve cluster generation and quantification. In addition to the core algorithms, I investigated modified strategies, such as implementing DBSCAN iteratively and using DTW-based cluster comparison to address critical challenges. Rigorous experimentation allowed to evaluate cluster quality based on predefined conditions, reducing ambiguity in classifying new data while enhancing the separation of distinct patterns. I assessed the strengths and weaknesses of each approach, ultimately identifying a promising pipeline for classifying time series data into well-defined clusters. After fine-tuning hyperparameters, I developed a custom prediction method inspired by Kernel Density Estimation (KDE). This method utilizes the generated clusters to predict the pass/fail outcome of new bolting cases during testing by analyzing their torque vs. time plots.

In conclusion, the comprehensive approach, which combines data analysis techniques with machine learning, yielded a robust methodology for analyzing bolting connection patterns. By extracting meaningful clusters and optimizing cluster quality, I provide a method to classify new bolting cases into OK, NOT_OK, or ambiguous categories. Consequently, this research improves understanding of bolting connections and provides a useful tool for quality control and safety assessment in the production industry.

## Features

- Preprocessing of raw data for better noise handling and alignment.
- Application of clustering and classification algorithms for data analysis.
- Integration of advanced techniques like:
  - Dynamic Time Warping (DTW)
  - Density-Based Spatial Clustering (DBSCAN)
  - Autoencoders for anomaly detection
- Evaluation of cluster quality and classification results.
- Real-time classification capabilities for new data points.

## Key Benefits

- Enhanced detection of problematic bolting cases in production processes.
- Improved understanding of bolting patterns through clustering.
- Reduction in misclassification and ambiguous cases.
- Integration-ready solutions for production processes with appropriate adjustments.

## NOTE

This project was undertaken as part of my work at Fraunhofer IPT, Aachen (DE). Due to a Non-Disclosure Agreement, I am unable to share specific details, data, or code related to this project. The repository provides only general information about my involvement and the skills utilized during its development.
If you would like to know any more information than already mentioned in the repository, feel free to connect with me.