# Customer Segmentation using KMeans Clustering

This project demonstrates customer segmentation using KMeans clustering on a mall customer dataset. The goal is to identify distinct customer groups for targeted marketing strategies.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Customer segmentation is a powerful technique for identifying and understanding distinct customer groups, enabling businesses to optimize marketing efforts. In this project, we use KMeans clustering to segment customers based on their spending habits and demographics.

## Dataset
The dataset used in this project is `mall_customers.csv`, which contains the following features:
- **CustomerID**: Unique identifier for each customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income**: Annual income of the customer
- **Spending Score**: Score assigned by the mall based on customer spending behavior

## Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/RahulSingh-DS/Customer-Segmentation-Project.git
   cd Customer-Segmentation-Project
2. **Install dependencies**
   - It’s recommended to use a virtual environment
   - python3 -m venv env
     source env/bin/activate      # On Windows, use `env\Scripts\activate`
   - **Install required packages:**
   - pip install -r requirements.txt

**Project Structure**
- data/: Contains the dataset file.
- notebooks/: Contains Jupyter notebooks for code,visualizations and analysis.
- src/: Contains the main Python script for KMeans Clustering.
- README.md: Provides an overview of the project.
- requirements.txt: Lists all dependencies needed for the project.

**License**
  - This project is licensed under the MIT License.
