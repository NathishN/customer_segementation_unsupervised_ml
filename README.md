# customer_segementation_unsupervised_ml
📊 Customer Segmentation using Unsupervised Learning
📝 Project Overview
This project demonstrates an end-to-end Data Analytics and Machine Learning workflow focused on customer segmentation. Using unsupervised learning techniques, the project identifies hidden patterns in customer behavior to support data-driven marketing decisions for businesses dealing with unlabeled data.

🎯 Business Objective
The primary goal is to help a business understand its diverse customer base to enable:

Targeted Marketing: Segment customers based on demographic and purchasing behavior.

Personalization: Identify meaningful customer groups to tailor communication and offers.

ROI Improvement: Enable data-driven strategies to improve marketing return on investment and retention.

🗃 Dataset Overview
The analysis is performed on a dataset containing information for 2,240 customers, including:

Demographics: Age, income, education, and marital status.

Spending Behavior: Consumption across product categories (Wines, Fruits, Meat, Fish, etc.).

Campaign Response: History of engagement with marketing offers.

Enrollment: Date the customer joined the company database.

🛠 Tech Stack
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (StandardScaler, PCA, KMeans, AgglomerativeClustering), Yellowbrick (KElbowVisualizer).

⚙️ Project Workflow
Data Cleaning: Handled missing values (dropping 24 rows with missing income) and converted date strings into datetime objects.

Feature Engineering: * Created a "Customer_For" feature indicating loyalty duration.

Derived "Age" from birth year.

Calculated "Spent" as the total expenditure across all categories.

Simplified "Family_Size", "Education", and "Living_With" categories for better model performance.

Exploratory Data Analysis (EDA): Visualized feature distributions and identified spending trends using Seaborn pair plots.

Data Preprocessing: scaled features using StandardScaler and reduced dimensionality using Principal Component Analysis (PCA) to handle multicollinearity.

Clustering:

Used the Elbow Method to determine the optimal number of clusters.

Applied K-Means Clustering and Agglomerative Clustering to segment the population.

📌 Key Insights & Recommendations
Segment Identification: Customers are successfully grouped into distinct behavior-based clusters.

High-Value Targets: Identified a segment of high-spending customers with consistent patterns; recommended for loyalty programs and premium offers.

Engagement Strategy: Low-engagement segments were identified for targeted discount campaigns to boost interaction.
