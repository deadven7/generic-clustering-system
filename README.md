# Data Mining Project: Netflix Content-Based Recommender System

## Project Overview
This project explores the application of data mining techniques to create a content-based recommender system for Netflix shows. The project leverages a detailed dataset containing various attributes of Netflix content, including titles, directors, cast, and genres. Key aspects of the project include data preprocessing, exploratory data analysis, clustering implementations, and building a recommender system.

## Features
- **Data Importation and Cleaning**: Initial steps include importing necessary libraries and datasets, followed by cleaning the data to rectify issues such as missing values and incorrect formats.
- **Exploratory Data Analysis (EDA)**: Conducted to understand the underlying patterns and distributions within the data.
- **Data Preprocessing**: Involves text preprocessing, tokenization, lemmatization, and vectorization to prepare data for modeling.
- **Clustering Implementation**: Uses K-Means and hierarchical clustering to group similar content, helping in the analysis and recommendation processes.
- **Content-Based Recommender System**: Developed using cosine similarity measures to recommend similar shows based on user preferences.

## Methodologies
### Data Preparation
- The dataset includes over 7,000 records with attributes related to Netflix titles such as genre, cast, and descriptions.
- Cleaning involved removing non-ASCII characters, stopwords, and applying lowercasing for uniformity.

### Clustering Techniques
- **K-Means Clustering**: Applied to determine inherent groupings among the shows based on features like genre and cast.
- **Hierarchical Clustering**: Utilized to visually and analytically assess the data's hierarchical structure.

### Recommender System
- Built by calculating cosine similarity among shows based on their vectorized content descriptions.
- Provides recommendations by identifying shows with the highest similarity scores to a given input.

## Results
- The clustering models provided insights into the categorization of content, which were used to enhance the recommender system's accuracy.
- The recommender system effectively suggests similar shows, enhancing user engagement by personalizing content recommendations.

## Visual Insights

### Data Analysis

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/16e83ece-9ab5-4406-9003-c5bcc90d265a)


### Cluster Analysis

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/cfd32f86-6d9b-46c6-832e-d7cbbfde0c0f)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/7e758638-e2eb-4a96-9dfe-a55881768026)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/4b62e258-1f7c-400e-a51b-fbe231e727ee)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/3dec818e-0e3e-4299-a396-8cb245587c91)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/d2cfeefb-5ad9-494f-8145-3a6bcb3795a6)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/5d2e6d49-1ecf-4195-b56a-1bfc9b861fa7)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/8ec92a1e-c922-4b99-b4e2-bfeb5cb0544b)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/ea8c72b1-7e4d-4874-a67a-29f3cbaf8a35)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/94d68821-bdff-4394-a83a-aff1d35d1e20)

### Content Recommendations

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/3699d252-d53a-4f74-86a1-d388721335fe)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/49167054-fd24-44d4-b255-2923253bb7a1)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/1fc17969-b56c-441d-aa18-e1937b90d913)

![image](https://github.com/deadven7/generic-clustering-system/assets/43636138/439d4eea-35aa-4027-a874-65120661009b)

## Conclusion
The project demonstrates the effectiveness of data mining techniques in building a sophisticated recommender system for streaming platforms. The implementation of clustering and similarity measures significantly improves the recommendation quality, providing viewers with content aligned to their preferences.

## Future Work
- Explore more advanced machine learning models for better accuracy in recommendations.
- Expand the dataset to include additional features such as viewer ratings and reviews for more nuanced analysis.

## Team Contributions
- Amaan Vora
- Jahnavi Shah
- Rutvik Deshpande
- Priyal Shaha
