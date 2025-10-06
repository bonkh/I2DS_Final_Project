# Ho Chi Minh City Rental and Selling Real Estate Analysis 
Final project for Introduction to Data Science course - HCMUS 2023. 

*Note: Project was completed before the change in administrative geography in 2025 (which still contain district level)* 

| ID | Member | Section |
|----|---------|--------|
| 21120275 | Huynh Cao Khoi | Selling real estate (Part 1) |
| 21120308 | Pham Le Tu Nhi | Rental real estate (Part 2) | 

## 1. Introduction 
The project aim to collect, analyse and build ML models to predict real estate services cost in Ho Chi Minh city, by going step by step through phases of a Data Science project. The data is collected from [batdongsan.com](https://batdongsan.com.vn/)

## 2. Technologies 
The following technologies are used in the project:
- `cloudscraper`: Light-weight library for web scraping
- `pandas`: Dataframe manipulation for data cleaning and processing
- `numpy`: Array manipulation for basic statistics analysis
- `matplotlib`: Data visualization
- `scikit-learn`: Build and train ML models
- `streamlit`: Deployment for real estate cost prediction web service

## 3. Results 
We found that there are a great variation of cost between the **type** and **location** of a property. (We also need to emphasise that the data is collect from 1 website at 1 period of time (the end months of 2023), which could introduce great bias).

### Rental properties 
- Rental real estate divides into living and commercial types: apartments dominate Districts 2 and 7, rented rooms in Tân Bình and Bình Thạnh; warehouses appear in suburban areas (Bình Tân, District 2), while offices and front-houses cluster in central districts (1, 2, 3). 


### Selling properties  




Work management resource: [Notion](https://hickory-adasaurus-926.notion.site/IDS-Team-8a6f7c93f2834c759af4f77fdad9f2ef?pvs=74).

Demo of my team deployed model: [DEMO](https://i2ds-finalproject.streamlit.app/)
