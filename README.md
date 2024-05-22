Used Cars Recommendation System using AutoEncoders
Overview
This project aims to develop a recommendation system for the used car market by leveraging advanced machine learning techniques. By utilizing Denoising AutoEncoders (DAE) and Approximate Nearest Neighbors (ANN), the system generates personalized car recommendations based on user input and car attributes. The project involves extensive Exploratory Data Analysis (EDA) and data preprocessing to create robust representations of vehicle features.

Project Structure
data/: Contains the dataset used for the project.
notebooks/: Jupyter notebooks for data exploration, preprocessing, model training, and evaluation.
src/: Source code for data preprocessing, model definition, training scripts, and evaluation metrics.
reports/: Generated analysis reports and visualizations.
README.md: Project overview and instructions.
Objectives
Construct a recommendation system for used cars based on user input.
Utilize Denoising AutoEncoders (DAE) to filter noise from the dataset and learn robust representations of car attributes.
Evaluate model performance using metrics like Mean Squared Error (MSE).
Provide personalized and relevant car recommendations to improve user satisfaction in the used car market.
Data Collection and Pre-Processing
Dataset: The dataset contains 66 features including categorical and numerical variables such as model name, mileage, year, fuel type, and transmission.
Handling Missing Values: Missing values were handled by dropping columns with significant missing data and imputing values where necessary.
Encoding Categorical Variables: Applied One-Hot Encoding and Label Encoding for categorical variables.
Scaling Numerical Features: Used Min-Max Scaling and Standard Scaling for numerical features.
Exploratory Data Analysis (EDA)
Price and Mileage Relationship: Analyzed the negative correlation between car price and mileage.
Year and Price Relationship: Found a positive correlation between the manufacture year and car price.
Fuel Type and Price Relationship: Observed higher prices for alternative fuel vehicles.
Body Type and Price Relationship: Identified higher average prices for SUVs and trucks compared to sedans and hatchbacks.
Transmission Type and Price Relationship: Noted higher prices for cars with automatic transmissions.
Results
Model Performance: Denoising Autoencoders were used to learn complex representations of the data. The model was trained for multiple epochs, achieving a Mean Squared Error (MSE) of 0.6434 after 40 epochs.
Recommendations: The system generates recommendations for the top 6 related vehicles based on user input.
Conclusion
This project successfully developed a recommendation system for used cars, utilizing Denoising AutoEncoders to filter noise and learn robust representations of car features. The system provides personalized and relevant recommendations, enhancing the user experience in the competitive used car market.

References
US Used Cars Dataset by Ananay Mital.
Cheng, S., & Wang, T. (2022). Car recommendation system for dealers in different European countries. In 14th International Conference on Computer Research and Development (ICCRD), IEEE.
Huang, J., et al. (2023). A latent factor-based bayesian neural networks model in cloud platform for used car price prediction. IEEE Transactions on Engineering Management.
