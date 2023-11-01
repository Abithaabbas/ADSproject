# Customer Segmentation Project With Data Science

## Overview

 A customer segmentation project using a mall dataset aims to divide the mall's customer base into distinct groups based on various characteristics and behaviors. This segmentation process helps businesses understand their customers better, tailor marketing strategies, improve customer experiences, and ultimately increase profitability.

## Table of Contents

[Getting Started](https://github.com/Abithaabbas/ADSproject/edit/main/README.md#getting-started)

[Data](https://github.com/Abithaabbas/ADSproject/edit/main/README.md#data)

[methods](https://github.com/Abithaabbas/ADSproject/edit/main/README.md#methods)

[Results](https://github.com/Abithaabbas/ADSproject/edit/main/README.md#results)


## Getting Started

*Prerequisites:*

 Jupyter Notebook Software need to be installed before using this project.or u can use Google Colab instead.

     https://jupyter.org/    https://colab.google/

*Installation:*

  1. Clone the repository:
  
    git clone https://github.com/Samnasamna/ADS-project1.git

   2.Installing libraries

   -> numpy
  
   -> pandas
  
   -> matplotlib
  
   -> seaborn
  
   -> sklearn


 ## Data

 *Dataset:*

 Gathered  customer data, including demographics, purchase history, website interactions, and more from kaggle.com website.

    Dataset Link: https://www.kaggle.com/datasets/akram24/mall-customers 


 
 *Data Preprocessing:*

 Cleaned the data by removing unwanted columns from the dataset, handle missing values by applying a numerical value to it, outliers, and performed data transformation.

    encoder = LabelEncoder()
    data['Gender'] = encoder.fit_transform(data['Gender'])
    gender_mapping = {index: label for index, label in enumerate(encoder.classes_)}
    gender_mapping

## methods

*Clustering Algorithms:* 

  Employ unsupervised learning techniques like k-means, hierarchical clustering, or latent class analysis to group customers based on similarities.

 
*Dimensionality Reduction:*

  Use techniques like PCA (Principal Component Analysis) and t-sne to reduce dimensionality and improve the efficiency of clustering algorithms.


## Results

Generate visualizations (scatter plots, heatmaps, etc.) to understand the distribution of customer segments.

From the Count plot it is observed that the number of Female customers are more that the total number of Male customers.

 
 

it is evident that there are 3 age groups that are more frequently shop at the mall, they are: 15-22 years, 30-40 years and 45-50 years.
