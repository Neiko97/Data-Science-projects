# Data Science Portfolio

Hello, I'm Neiko, a junior data scientist with a deep passion for exploring and evolving in the dynamic domain of data science. Despite the challenges of this field, I find joy and excitement in continuously learning and applying new techniques. Building this portfolio is not only a fun and passionate endeavor for me but also a strategic step towards personal growth. Through this platform, I aim to showcase my skills, contributing to my evolution in the field and opening doors to exciting opportunities in the future.

## Project 1: Predict Horse Health Outcome

- This project aims to predict the health outcome of horses. The data has been retrieved from [Kaggle](https://www.kaggle.com/competitions/playground-series-s3e22) and is classified as a beginner-level competition.

- In this notebook, you will find various steps detailing my approach to this task:
  - First, I conducted a simple exploratory analysis to identify statistical significance among different features.
  - Next, I incorporated visualizations to uncover hidden insights.
  - Finally, I trained various models to determine the most suitable algorithm for this type of problem.

- It was determined that XGBoost produced the most satisfying results. Since the data lacks inference data for testing, this project relies solely on the split train data for training purposes.

## Project 2: Sales Analysis on Power BI
This project is a demonstration of my Power BI proficiency, highlighting various aspects of my skills in data analysis and visualization. The report features a well-structured data model that I meticulously built. Within, you'll encounter diverse measurements, demonstrating my skills in using DAX (Data Analysis Expressions). The report also showcases my storytelling ability, weaving insights seamlessly throughout the analysis. Despite the simplicity of the dashboard, it serves as a powerful example of my capabilities with this tool, offering a glimpse into the depth and breadth of my Power BI skills. The data for this project was sourced from [LearnDAX](https://www.learndax.com/power-bi-sample-data-for-beginners-to-download/), a website dedicated to providing sample data for beginners in Power BI.

## Project 3: GAN Face to Cartoon Training

### Project Overview

In this project, the goal is to construct a cycleGAN architecture from scratch using PyTorch. The training procedure involves utilizing two distinct style datasets: the Flickr Faces dataset and the Google Cartoon dataset.

#### Objective

The primary objective of this project is to transform human faces into cartoons and vice versa. By leveraging the power of CycleGAN, we aim to achieve realistic and high-quality results in the translation between these two styles.

### Implementation Details

The model has been implemented using object-oriented programming principles, inheriting from the PyTorch `nn` module. This design choice enhances modularity and code organization, making the architecture more comprehensible and extensible.

### Datasets Used

1. **Flickr Faces Dataset:** A dataset containing human faces from Flickr, providing a diverse range of facial expressions and variations.
   
2. **Google Cartoon Dataset:** This dataset consists of cartoon images from Google, offering a distinct and artistic style for comparison and transformation.

### Training 

The training process, including the final results, is documented in on a colab notebook. The notebook serves as a comprehensive guide, detailing the training steps and showcasing the obtained results.
You can see the results [here](https://colab.research.google.com/drive/1uzPu2HOGsv94fulyr7U8SE_5fDnKnCm2?usp=sharing)

### Note

Currently, the project is temporarily on hold due to the unavailability of necessary training materials. Unfortunately, Colab does not offer a paid subscription plan in Luxembourg, and opting for a cloud solution appears to be too expensive. Once I secure the appropriate materials, I will proceed with the continuation of the training process.

## Project 4: Retail Sales Prediction with Time Series Analysis

### Project Overview

In this dynamic time series project, the aim is to predict sales for an American retail store by leveraging historical sales data obtained from Walmart. The project unfolds with an initial exploratory analysis conducted on PowerBI, offering a comprehensive view of the data and insights into the unique situations across 45 different stores.

#### Objective

The primary objective of this project is to employ machine learning and deep learning techniques, specifically the Random Forest Regressor, XGBoost and LSTM from the scikit-learn, xgboost and tensorflow/keras libraries, to accurately forecast future sales. The predictive models are designed to enhance operational decision-making for the retail store.

### Implementation Details

The ML/DL models are implemented using the scikit-learn, xgboost and tensorflow/keras libraries, showcasing a structured and well-documented approach.

### Data Sources

The project utilizes historical sales data from Walmart found on [Kaggle](https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast) , providing a robust foundation for time series analysis. The dataset captures the nuances of sales patterns across various stores, contributing to the accuracy of the predictive models.

### Training

The training process involves the application of machine learning and deep learning algorithms, specifically the Random Forest Regressor, XGBoost and LSTM, on the historical sales data. The results and insights obtained from the trained models contribute to informed decision-making for future sales predictions.

### Presentation

The finalized data will be stored on a dedicated database server, enabling the final model to autonomously generate predictions. To enhance accessibility and decision-making, the project's results will be visually presented on a PowerBI dashboard, providing stakeholders with a user-friendly interface for actionable insights.

### Note
Intermediate results are available on my colab notebook [here](https://colab.research.google.com/drive/1UL3iTb08Gz4ax5vymlD7VeSqtWqoI8E2?usp=sharing).
