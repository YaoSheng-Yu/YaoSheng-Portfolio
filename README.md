# Yao-Sheng's Portfolio

# [Project 1: Wine Clustering Analysis 🍷](https://github.com/YaoSheng-Yu/Wine_Cluster_Analysis)

-  Explore the underlying structure and natural groupings within a labeled wine dataset to uncover hidden patterns and validate the labels.
-  Building **K-means Clustering** & **EM Algorithm** models with **R**.
-  Creating animated plots to show the changes in each iteration.
-  In depth evaluating and analysing the result and advantages of the two models.

![K-means GIF](./plots/EM_wine_animation.gif)


# [Project 2: House Prices Advanced Regression Techniques 🏠](https://github.com/YaoSheng-Yu/house-prices-advanced-regression-techniques)

- Undertaking comprehensive **Exploratory Data Analysis** to glean insights from the dataset.
- Encoding categorical variables using the **smoothed median** of their corresponding SalePrice, ensuring minimal data leakage.
- Leveraging Random Forests in combination with Recursive Feature Elimination (RFE) for efficient **feature selection**.
- Optimizing **Gradient Boosting Regression** through Grid Search, enhancing model performance and accuracy.

![Sale Price Distribution](plots/price_dist.png)


# [Project 3: Give Me Some Credit 🏦](https://github.com/YaoSheng-Yu/Give-Me-Some-Credit---predicting-due-delinquency)

- Handling missing 'Monthly Income' data by segmenting into two age groups and employing **RandomForestRegressor** for imputation.
- Checking data correlation, removing features with high **multicollinearity** to ensure model robustness.
- Using Grid Search coupled with **ROC_AUC** metric to rigorously evaluate and optimize four distinct classifiers.
- Addressing class imbalance through **under-sampling** techniques, ensuring a balanced target distribution for enhanced predictive accuracy.

![Age and Income Relationship](plots/age.png)


# [Project 4: NBA Advance Stats Analysis 🏀](https://github.com/YaoSheng-Yu/NBA_advance_stats_analysis)

- Conducted a comprehensive analysis of NBA game data to explore the impact of advanced basketball statistics on team win percentages.
- Utilized **Ridge Regression** as the primary model, which provided the most balanced results, achieving an MSE of 103.66 and explaining approximately 51% of the variance in win percentage.
- The project underscores the significant influence of **three-point shooting efficiency, rebound control, and true shooting percentage** on the outcomes of NBA games.

![scatter_nba.png](plots/scatter_nba.png)  

# [Project 5: Power Of Math ☁️](https://dev.d162d5jew5ux0o.amplifyapp.com/)

- A simple AWS full-stack web application that calculates the result of a base number raised to an exponent.  
- Frontend: Hosted using AWS Amplify, allowing for easy deployment and access.  
- Backend: Utilizes AWS Lambda for serverless execution of the mathematical operations.  
- API Integration: API Gateway is used to connect the frontend and backend, enabling secure data transfer.  
- Database: The results are stored in a DynamoDB table for persistence and future use.  

![scatter_nba.png](plots/PowerOfMath.png)  


# [Project 6: Traveling Salesman Problem-TSP 👨‍💼](https://github.com/YaoSheng-Yu/Traveling-Salesman-Problem-TSP)

- Developing an advanced solution to the classic **Traveling Salesman Problem (TSP)** utilizing **heuristic** algorithms.
- Efficiently implementing **Kruskal's Algorithm** to derive a **Minimum Spanning Tree (MST)** for the given weighted graph.
- Employing **Depth-First Search (DFS)** traversal on the MST to **approximate** a TSP solution, showcasing algorithmic prowess.
- Including utility scripts to generate graph test cases, enabling both best-case and worst-case scenario analysis for thorough evaluation.

![ratio_of_TSP.png](plots/ratio_of_TSP.png)  


# [Project 7: Rat USV Identification 🐀](https://github.com/YaoSheng-Yu/Rat-calls-audio-preprocessing-and-identification)

- Conducted thorough EDA to visualize noise distribution and initial accuracy, and to guide the noise cleaning process.
- Implemented advanced noise cleaning techniques, including **bandstop filters**, to isolate and enhance USV signals from background noise.
- Utilized the DeepSqueak software with YOLO model for object detection, and optimized the threshold parameters to significantly increase the precision and accuracy of USV detection.  

<img src="plots/filtering_lower_freq.png" alt="Filtering Lower Frequency" width="120%" />



