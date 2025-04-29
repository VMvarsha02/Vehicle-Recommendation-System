# Vehicle-Recommendation-System

Problem Statement:
With an ever-growing number of vehicle options, users often face difficulty in choosing the right vehicle that fits their needs and preferences. Traditional methods rely heavily on manual filtering and may not offer personalized suggestions.

Proposed Solution:
A Vehicle Recommendation System that uses machine learning to provide personalized vehicle suggestions based on user inputs such as budget, fuel type, mileage, and engine capacity.

Working Methodology:
The system first cleans and processes vehicle dataset features. It uses a content-based filtering approach, leveraging cosine similarity on selected features (e.g., engine, power, mileage, fuel type) to identify vehicles similar to user preferences. A web interface collects user inputs and displays top recommendations ranked by similarity scores.
