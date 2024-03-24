<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h1>GamePopularity Project</h1>
<p>The GamePopularity project focuses on analyzing the popularity of various video games. It involves crawling data from Steam's website, cleaning up the data, performing exploratory data analysis (EDA), and applying machine learning algorithms to predict game success.</p>

<h2>Technologies Used</h2>
<p>The project employs the following technologies, libraries, and algorithms:</p>
<ul>
<li>pandas: Data manipulation and analysis library in Python.</li>
<li>requests: Python library for making HTTP requests.</li>
<li>Beautiful Soup: Python library for pulling data out of HTML and XML files.</li>
<li>matplotlib: Data visualization library for creating static, interactive, and animated visualizations in Python.</li>
<li>scikit-learn: Machine learning library for Python.</li>
<li>numpy: Library for numerical computing in Python.</li>
<li>seaborn: Statistical data visualization library based on matplotlib.</li>
<li>Decision Tree Algorithm: Supervised learning algorithm used for classification.</li>
<li>K-Nearest Neighbors (KNN): Classification algorithm used for pattern recognition.</li>
</ul>

<h2>Overview</h2>
<p>The GamePopularity project involves the following steps:</p>
<ol>
<li>Crawling: Data is scraped from Steam's website using Python libraries such as requests and Beautiful Soup. Information like game names, release dates, genres, prices, reviews, and other attributes are collected.</li>
<li>Data Cleanup: The collected data is cleaned by removing duplicates, handling missing values, and preprocessing columns for analysis.</li>
<li>Exploratory Data Analysis (EDA): Statistical techniques and visualizations are applied to understand the data distribution, relationships between variables, and identify patterns.</li>
<li>Machine Learning: Various machine learning algorithms such as Decision Tree and KNN are applied to predict the success of games based on features like genre, reviews, and price.</li>
</ol>

<h2>Project Structure</h2>
<p>The project consists of several Python scripts:</p>
<ul>
<li>GamePopularity-Crawling.py: Crawls data from Steam's website and saves it to a CSV file.</li>
<li>GamePopularity-DataCleanup.py: Cleans up the crawled data by removing duplicates and handling missing values.</li>
<li>GamePopularity-EDA.py: Performs exploratory data analysis on the cleaned data to gain insights.</li>
<li>GamePopularity-MachineLearning.py: Applies machine learning algorithms to predict game success based on features.</li>
</ul>

<h2>Deployment</h2>
<p>The project can be deployed locally on any machine with Python installed. It requires the installation of various libraries mentioned above using pip or conda package managers. Additionally, the dataset can be hosted on cloud platforms for easy access and sharing.</p>
</body>
</html>