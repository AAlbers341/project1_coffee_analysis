<p align="center">
  <img width="400" height="400" src="https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/e9f9f422-f019-46ba-9148-bd1f56829aaf">
</p>

# El Nino/La Nina impacts on Global Coffee Prices and Production
### Purpose
Analyze how coffee prices have shown significant variation over the years, influenced by a variety of factors including market dynamics and possibly meteorological phenomena like El Nino and La Nina.  ​
### Key Objectives
* Identify coffee producing countries and top 10 producers.
* Compute total and yearly average production.
* Display Arabica and Robusta coffee prices fluctuation over the years.
* From coffee producing countries, how has El Nino/La Nina patterns impacted coffee prices?
* Show the correlation coefficient between yearly average coffee price and El Nino/La Nina patterns and their effect on coffee prices.
* Evaluate the correlation between El Nino/La Nina patterns and their effect on different types of coffee.
* Identify the countries that have been most impacted by irregular El Nino/La Nina patterns and how this meteorological phenomena has influenced production outputs.
### Key Findings
* Production data emphasizes the dominance of certain countries in coffee production, particularly Brazil.
* The correlation between coffee prices and the Oceanic Index suggests that while meteorological conditions may have some impact on coffee prices, they are likely not the sole influencing factor.
* Arabica coffee generally has a higher price than Robusta.
* The price of Arabica coffee beans shows more volatility over the years compared to Robusta.
* There are notable peaks in Arabica prices around the years 1997, 2022, and 2011 which is the highest on the graph.
* For Robusta, the prices also peaked around 1995 and 2011 but are less pronounced than Arabica's peaks.
### Table of Contents - IN PROGRESS
1. [Tech Stack](# 1. Tech Stack)
3. [Data Sources] (# )
4. [Background](# )
5. [What is El Nino and La Nina?] (# )
6. [EDA Notebooks] (# )

### 1. Tech Stack
| Python Library  | Usage |
| ------------- | ------------- |
|![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/8841ac4f-3cbe-49c0-a2f4-c0acb1100224)  | Data manipulation and analysis  |
| ![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/4bf0c856-4875-4ff1-8ebd-03c0e66ebd14) | Numerical computations  |
| ![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/0edbd134-7e50-4c13-9a74-4f6b8350ba57) | 2D plotting  |
| ![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/76cae272-4bcc-4ab2-a376-880cd1d28190) | High-level plotting API   |
| ![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/3e7c0369-6e67-4080-81bc-ee7d214f80c0) |  Scientific and technical computing  |

### 2. Data Sources - IN PROGRESS
| Data Source  | Usage |
| ------------- | ------------- |
| FRED Economic Data - St. Louis FED  | Content Cell  |
| Coffee Dataset - Kaggle  | Content Cell  |
| El Nino & La Nina Dataset - Kaggle  | Content Cell  |
| Golden Gate Weather Services  | Content Cell  |
| City Weather Coordinates  | Content Cell  |

### 3. Background
Coffee, a staple in the morning routine of 63% of Americans, is influenced by shifting oceanic patterns. This change raises questions about the fluctuating coffee prices in the top 10 coffee-producing nations. Analyzing global coffee prices extends beyond a single commodity; it offers a window into the complex interaction between economic and environmental dynamics. 

Key factors in growing coffee plants is temperature, rainfall, and elevation:

**Arabica**
* Temp: 73°F – 82°F; does not tolerate heat, does not thrive if temps vary much outside of given range 
* Rainfall: 60-80 inches per year, with a dry period of 2-3 months
* Elevation: 2000-6500 ft
* Very temperamental if weather varies outside of the given ranges

**Robusta**
* Temp: 75.2°F-86°F; is heat tolerant
* Rainfall: 60-80 inches per year, with a dry period of 2-3 months
* Elevation: sea level to 600-1970 ft
* Tougher, hardier plant overall – much more forgiving when weather is outside of the given parameters
### 4. What is El Nino and La Nina?
El Nino and La Nina are part of a natural climatter pattern that occurs in the Pacific Ocean, affecting weather across the globe. 
* **El Nino** happens when **_warm water_** in the Pacific Ocean near the equator moves towards the Americas, changing weather patterns like bringing more rain to some places and causing droughts in others.
* **La Nina** is its opposite; **_cooler waters_** surface in the Pacific, which can lead to drier, warmer weather in some parts of the world and wetter conditions in others.

_When one side is warm, the other is cool, and this influences weather far beyond the Pacific_.
### 5. EDA Notebooks
#### 5.1 Coffee Production Analysis
##### Coffee Producing Countries
This notebook delves into global coffee production, emphasizing the top 10 coffee-producing countries. It integrates geographic data with production statistics to offer a perspective on production volumes and trends across key regions. **The analysis focus is on identifying leading producers and analyzing changes in their output over time**.

![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/1b3f04d6-80c8-4ce4-b858-b6340871f201)
SOURCE: [(_coffee_production.ipynb_)](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/EDA/coffee_production.ipynb)

##### Top 10 Coffee Producing Countries
![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/782fb843-7072-43e6-a223-51527ebff782)

SOURCE: [(_coffee_production.ipynb_)](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/EDA/coffee_production.ipynb)

#### 5.2 El Nino/La Nina Analysis
Our analysis reveals that between 1990 and 2017, El Nino and La Nina events had a predominant share of neutral years regarding oceanic temperatures. **El Nino exhibited a 30% occurrence rate with weak intensity, while La Nina showed a 14% occurrence with moderate intensity**. This analysis is crucial in understanding the climatic influences on agricultural outputs, including coffee.

![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/a7e33e91-ce6f-4a36-bf57-392eb94f20d7)

SOURCE: [(_El-Nina_La-Nina_analysis.ipynb_)](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/EDA/El-Nina_La-Nina_analysis.ipynb)

#### 5.3 Coffee Data Merged
This  analysis investigates the relationship between El Nino/La Nina patterns and coffee prices. It contrasts the prices of Robusta and Arabica coffee with the respective climatic indices, also examining the correlation between total coffee production and these weather phenomena. The analysis focus is on discerning patterns and correlations between climatic changes and coffee market dynamics.

**The graph Arabica Coffee Price vs. El Nino Index below serves as an example of the Coffee Data Merged Notebook analysis**. It shows a scatter plot with Arabica coffee prices (in US cents per pound) on the X-axis and the El Nino index on the Y-axis. A regression line is plotted through the data points.


**Implications:** _The r-value is 0.33391089859185084_, indicates a _moderate positive correlation_ between Arabica coffee prices and the El Nino index. This suggests that as the El Nino index increases, there is a tendency for the prices of Arabica coffee to also increase.  It could be that El Nino conditions lead to decreased production and hence higher prices, or it could be that other factors are influencing both the El Nino index and coffee prices.

![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/7be35f7c-0897-4cfb-830e-214282ce6cbb)

SOURCE: ([_coffee_data_merged.ipynb_)](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/EDA/coffee_data_merged.ipynb)

#### 5.4 Coffee Prices
The notebook offers an exploration of Arabica and Robusta coffee prices from 1990 to 2023. **It highlights that Arabica coffee is historically pricier than Robusta, with Arabica prices ranging from $61.46 to $271.11 per lb and Robusta prices fluctuating between $27.51 and $125.56 per lb**. The analysis points out significant price shifts, notably a decrease in the late 1990s, a bottoming out in 2002, and a rise into 2006, with exponential growth for Arabica in 2011. These trends provide insights into market behavior and pricing dynamics over more than three decades.

![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/6391e76f-2633-446d-ac23-e6471f3e3818)

SOURCE: [(_coffee_prices.ipynb_)](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/EDA/coffee_prices.ipynb)



