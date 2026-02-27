**Netflix Movies and TV Shows Clustering (Unsupervised ML)**

This project applies unsupervised machine learning techniques to analyze the "DNA" of Netflix's content library. By grouping titles based on their mood, style, and themes, this project aims to build a more nuanced recommendation engine that goes beyond simple genre or language matching.

**Business Objectives**

* Better Recommendations ("The Vibe Matcher"): Moving beyond simple categories to suggest "hidden gems" (e.g., matching a dark futuristic thriller from the UK with a similar vibe from South Korea).

* Smarter Library ("The Content Map"): Mapping the entire library to identify over-saturated genres (like generic baking shows) and underserviced gaps (like mystery thrillers for teens).

* Smarter Search: Improving search results by understanding the "family" a show belongs to, allowing users to find content based on mood or concept rather than just exact title matches.

**Key Insights & Visualizations**

* The project includes an extensive Exploratory Data Analysis (EDA) of the Netflix dataset:

* Content Type: A comparison of the total volume of Movies vs. TV Shows in the library.

* Rating Distribution: Analysis of age ratings (e.g., TV-MA, TV-G) to understand audience targeting.

* Geographic Reach: Identification of the top 10 countries producing content, visualizing Netflix's global production footprint.

**Tech Stack**

* Language: Python

* Environment: Google Colab / Jupyter Notebook

* Libraries: * pandas for data manipulation

* matplotlib & seaborn for data visualization

* scikit-learn for unsupervised clustering algorithms

**Methodology**

* Problem Understanding: Defining how clustering solves real-world content delivery challenges.

* EDA & Visualization: Analyzing relationships between content type, ratings, and country of origin.

* Data Preprocessing: Cleaning text data and handling categorical features.

* Clustering: Implementing machine learning models to group similar content.

**Stakeholder Strategy:**

* Marketing: Creating targeted campaigns based on cluster preferences.

* Content Acquisition: Guiding future production by identifying under-represented clusters.

* UX Designers: Personalizing the homepage with "Category Rows" based on user clusters.

**How to Use**

* Clone the repository.

* Open NETFLIXclustering.ipynb in Google Colab or Jupyter.

* Ensure the dataset NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv is in the root directory.

Run all cells to generate analysis and clusters.

Developed by Sujal Singh Thakur
