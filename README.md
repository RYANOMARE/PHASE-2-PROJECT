# PHASE II PROJECT
**Authors** : 
1. ROSE KYALO
2. STACY KIRIIRI
3. ANGEL ATUNGIRE
4. BRYTONE OMARE

## Insights on Property Investment Profitability
![RASB Berry Image](/Image/RASB-berry.png "Image Alt Text" =900x500 class="blog-image")

<img src="./image/RASB-berry.png" alt="RASB Berry Image" width="900" height="500" class="blog-image">


## Overview

Welcome to the King County House Sales Analysis project, aimed at providing valuable insights and data-driven recommendations for RASB-berry Property Investors. In this project, we explore the King County House Sales dataset, which contains a wealth of information about house sales in a northwestern county. Our primary goal is to assist RASB-berry Property Investors in making informed investment decisions within the real estate market.

*Stakeholder: RASB-berry Property Investors*

RASB-berry Property Investors, a real estate investing business is seeking to expand it's market share by investing in a few properties. King County is on the radar and the company decided to seek to develop a new competitive edge throughout this phase of expansion by becomming a data-driven company. Thus, they decided to hire the consulting services of data scientists to provide data-driven recommendations on how to enter and behave within the target market. In this project, we're diving deep into the King County House Sales dataset to understand what makes properties profitable in King County's real estate market. Our main aim is to provide valuable insights to property investors who want to make smart investment decisions. We'll be looking at various aspects of properties, like their size, number of bedrooms, and condition, to see which factors have the most impact on the sale prices of houses. By doing this, we hope to help investors optimize their strategies and increase their chances of getting better returns in the King County real estate market.


## Business Problem

RASB-berry Property investors are looking to optimize their investment strategies by purchasing properties with the potential for high returns. They want to know which property attributes, such as square footage, number of bedrooms, and condition of the property, are most strongly correlated with sale prices. Objectives

RASB-berry Property Investors aims to address the following business objectives:

1. *Property Valuation*: Determine the factors that most strongly influence property values in the King County area. This includes understanding the impact of location, size, condition, and other property attributes on sale prices.

2. *Optimal Investment*: Identify neighborhoods or property characteristics that offer the best investment opportunities. RASB-berry Property Investors wants to focus their resources on properties with the highest potential for appreciation.

3. *Renovation Impact*: Provide insights into how home renovations may affect the estimated value of properties. RASB-berry Property Investors is interested in understanding which renovations lead to the most significant increases in property value.

4. *Market Trends*: Analyze historical sales data to uncover trends and patterns in the real estate market. This includes seasonal variations, price fluctuations, and any emerging market trends that can inform investment decisions.


## Methodology

To address these business objectives, we will employ multiple linear regression modeling techniques to analyze the dataset. This approach allows us to quantify the relationships between various factors and property values, providing valuable insights for RASB-berry Property Investors.

Our analysis will follow an iterative process, starting with a baseline model and progressively refining it to capture the most critical factors influencing property values. We will also explore data visualization and descriptive analysis to enhance our understanding of the dataset.

## Deliverables

The project will include the following deliverables:

1. A non-technical presentation for RASB-berry Property Investors to present key findings and recommendations.

2. A Jupyter Notebook containing the detailed analysis, modeling, and regression results.

3. A GitHub repository with project files, code, and documentation.


## Recommendations
1. Consider Property Attributes: Pay close attention to property attributes that have a significant impact on price. These include square footage of living space (sqft_living), the quality of the view (view), overall grade (grade), and whether the property is on a waterfront (waterfront). These factors are crucial in determining property values in the King County area. For example, most of the properties with higher interest rates were located near Lake Washington, thus explaining the waterfront and the view.

2. Location Matters: The zipcode, lat, and long variables have significant coefficients, indicating that the location of a property plays a substantial role in its price. Invest in neighborhoods that exhibit positive coefficients in these variables, as they are likely to offer better returns as we can see in this folium map, most of the houses are located North and near the Lake Washington.

3. Seasonal Trends: Analyzing seasonal trends in property prices using months yielded results that indicate the most houses are sold in the Spring time and Summer time and thus the Property Investors should maximize the months in this season especially May.

4. Renovation Strategies: Investigate how specific renovations or improvements impact property values. While the dataset may not directly include renovation data, you can explore correlations between renovation indicators and price to provide more detailed advice to homeowners.

5. Continuous Monitoring: Keep a close watch on the King County real estate market in regards to the recommendations above. Market
conditions can change over time, and it's essential to continuously monitor trends and adjust your investment strategies accordingly.

This project aims to empower RASB-berry Property Investors with actionable insights to support their real estate investment decisions. 

## LIMITATIONS
Limited Feature Set: The dataset may not include all the relevant features or variables that influence property prices. Other important factors, such as neighborhood crime rates, school quality, and proximity to amenities, may not be present in the dataset.
Temporal Data: The dataset may not include data on important temporal factors like economic conditions, interest rates, or changes in local regulations that can affect property prices.

Sample Size: The dataset's size may be limited, which can affect the robustness of predictive models, especially if you're working with small subsets of data.

Bias: The data may contain bias in terms of property types, locations, or price ranges, which can impact the generalizability of predictive models to other real estate markets.

Categorical Data: The dataset might have categorical variables that require encoding or transformation to be used effectively in predictive models.

Non-Stationarity: Real estate data often exhibits non-stationarity, meaning that trends and relationships can change over time. Accounting for this can be challenging.

Seasonality: Real estate markets can have seasonal patterns that are not explicitly captured in the dataset. For example, housing prices may vary based on the time of year.

Model Complexity: Depending on the complexity of the problem you're trying to solve, linear models or basic machine learning algorithms may not capture intricate patterns in the data.

Data Imbalance: If the dataset has an imbalanced distribution of target variables (e.g., a few high-value properties and many low-value properties), it can lead to modeling challenges.

Generalization: The dataset may represent a specific geographic area or time period. Models built on this data may not generalize well to different regions or time frames.

External Factors: Real estate prices can be influenced by external factors such as economic recessions or natural disasters, which may not be accounted for in the dataset.

To address these limitations and improve the accuracy of predictive projects, you can consider:

Collecting additional data from various sources to supplement the dataset.
Performing feature engineering to create new informative features.
Applying advanced modeling techniques and algorithms that can capture complex relationships.
Regularly updating and retraining models to adapt to changing market conditions.
Conducting thorough validation and testing to assess model performance and generalization.
It's important to approach predictive projects in real estate with a clear understanding of the data's limitations and to continuously refine models to achieve meaningful results.









