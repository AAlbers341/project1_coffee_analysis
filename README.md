<p align="center">
  <img width="400" height="400" src="https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/e9f9f422-f019-46ba-9148-bd1f56829aaf">
</p>

# El Nino/La Nina impacts on Global Coffee Prices and Production :coffee:
### Purpose
Analyze how **coffee prices** have shown significant variation over the years, influenced by a variety of factors including market dynamics and possibly meteorological phenomena like **El Nino and La Nina**.  ​
### Key Objectives
* Identify **coffee producing countries** and top 10 producers.
* Compute total and yearly average **production**.
* Display **Arabica** and **Robusta** coffee prices fluctuation over the years.
* From coffee producing countries, how has **El Nino/La Nina patterns** impacted coffee prices?
* Show the c**orrelation coefficient** between yearly average coffee price and El Nino/La Nina patterns and their effect on coffee prices.
* Evaluate the **correlation** between El Nino/La Nina patterns and their effect on different types of coffee.
* Identify the **countries** that have been most impacted by irregular **El Nino/La Nina** patterns and how this meteorological phenomena has influenced production outputs.
### Key Findings
* Production data emphasizes the **dominance** of certain countries in coffee production, particularly **Brazil**.
* The **correlation** between **coffee prices** and the **Oceanic Index** suggests that while meteorological conditions may have some impact on coffee prices, they are likely **_not_** the sole influencing factor.
* **Arabica** coffee generally has a higher **price** than **Robusta**.
* The price of Arabica coffee beans shows more **volatility** over the years compared to Robusta.
* There are notable **peaks** in **Arabica** prices around the **years** 1997, 2022, and 2011 which is the highest on the graph.
* For **Robusta**, the prices also **peaked** around 1995 and 2011 but are less pronounced than Arabica's peaks.
### Table of Contents
1. [Tech Stack](#1-tech-stack)
2. [Data Sources](#2-data-sources)
3. [Background](#3-background)
4. [What is El Nino and La Nina?](#4-what-is-el-nino-and-la-nina)
5. [EDA Notebooks](#5-eda-notebooks)
6. [Conclusion](#6-conclusion)

### 1. Tech Stack
| Python Library  | Usage |
| ------------- | ------------- |
|![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/8841ac4f-3cbe-49c0-a2f4-c0acb1100224)  | Data manipulation and analysis  |
| ![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/4bf0c856-4875-4ff1-8ebd-03c0e66ebd14) | Numerical computations  |
| ![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/0edbd134-7e50-4c13-9a74-4f6b8350ba57) | 2D plotting  |
| ![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/76cae272-4bcc-4ab2-a376-880cd1d28190) | High-level plotting API   |
| ![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/3e7c0369-6e67-4080-81bc-ee7d214f80c0) |  Scientific and technical computing  |

### 2. Data Sources
| Data Source  | Usage |
| ------------- | ------------- |
| [Arabica Coffee Dataset - St. Louis FED](https://fred.stlouisfed.org/series/PCOFFOTMUSDM)  | Coffee prices since 1990s to present day for Arabica  |
| [Robusta Coffee Dataset - St. Louis FED](https://fred.stlouisfed.org/series/PCOFFROBUSDM)  | Coffee prices since 1990s to present day for Robusta  |
| [Coffee Dataset - Kaggle](https://www.kaggle.com/datasets/michals22/coffee-dataset)  | Coffee production by country since 1990s  |
| [Encyclopedia Britannica](https://www.britannica.com/technology/regenerative-agriculture)  | General cultivation requirements for coffee beans  |
| [El Nino & La Nina Dataset - Kaggle](https://www.kaggle.com/datasets/bhaskar100/elnino-lanina)  |  Weather prediction of El Nino or La Nina year since 1950s  |
| [Golden Gate Weather Services](https://ggweather.com/enso/oni.htm)  | Oceanic El Nino/La Nina index values since 1950s  |
| [City Weather Coordinates](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/Data/Raw/coffee_cities_coordinates.csv)  | Coordinates of coffee-producing cities |

### 3. Background
Coffee, a staple in the morning routine of 63% of Americans, is influenced by shifting oceanic patterns. This change raises questions about the fluctuating coffee prices in the top 10 coffee-producing nations. Analyzing global coffee prices extends beyond a single commodity; it offers a window into the complex interaction between economic and environmental dynamics. 

Key factors in growing coffee plants is **temperature, rainfall, and elevation**:

**Arabica**
* **Temp:** 73°F – 82°F; does not tolerate heat, does not thrive if temps vary much outside of given range 
* **Rainfall:** 60-80 inches per year, with a dry period of 2-3 months
* **Elevation:** 2000-6500 ft
* Very temperamental if weather varies outside of the given ranges

**Robusta**
* **Temp:** 75.2°F-86°F; is heat tolerant
* **Rainfall:** 60-80 inches per year, with a dry period of 2-3 months
* **Elevation:** sea level to 600-1970 ft
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

##### Yearly Average Production by Country

![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/7c2af583-2867-4e59-96ef-083a3a08748f)

SOURCE: [(_coffee_production.ipynb_)](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/EDA/coffee_production.ipynb)

#### 5.2 El Nino/La Nina Analysis
Our analysis reveals that between 1990 and 2017, El Nino and La Nina events had a predominant share of neutral years regarding oceanic temperatures. **El Nino exhibited a 30% occurrence rate with weak intensity, while La Nina showed a 14% occurrence with moderate intensity**. This analysis is crucial in understanding the climatic influences on agricultural outputs, including coffee.

![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/a7e33e91-ce6f-4a36-bf57-392eb94f20d7)

SOURCE: [(_El-Nina_La-Nina_analysis.ipynb_)](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/EDA/El-Nina_La-Nina_analysis.ipynb)

#### 5.3 Coffee Data Merged
This  analysis investigates the relationship between El Nino/La Nina patterns and coffee prices. It contrasts the prices of Robusta and Arabica coffee with the respective climatic indices, also examining the correlation between total coffee production and these weather phenomena. The analysis focus is on discerning patterns and correlations between climatic changes and coffee market dynamics.

**The graph Arabica Coffee Price vs. El Nino Index below serves as an example of the Coffee Data Merged Notebook analysis**. It shows a scatter plot with Arabica coffee prices (in US cents per pound) on the X-axis and the El Nino index on the Y-axis. A regression line is plotted through the data points.


**Implications:** _The r-value is 0.33391089859185084_, indicates a _moderate positive correlation_ between Arabica coffee prices and the El Nino index. **This suggests that as the El Nino index increases, there is a tendency for the prices of Arabica coffee to also increase**. It could be that El Nino conditions lead to decreased production and hence higher prices, or it could be that other factors are influencing both the El Nino index and coffee prices.

![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/7be35f7c-0897-4cfb-830e-214282ce6cbb)

SOURCE: ([_coffee_data_merged.ipynb_)](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/EDA/coffee_data_merged.ipynb)

#### 5.4 Coffee Prices
The notebook illustrates the price fluctuations of Arabica and Robusta coffee from 1990 to 2017, with Arabica prices consistently outpacing Robusta. Arabica also demonstrates greater volatility, peaking dramatically around 2011 at over $2.50 per lb, whereas Robusta's peak at the same period is markedly lower. **The average prices over these years sit at $1.29 for Arabica and $0.74 for Robusta, emphasizing the premium placed on Arabica beans.** Both varieties show a general recovery in prices after early lows, with Arabica's lowest near the early 1990s and around 2001, while Robusta's is before 2004. Towards the end of the observed period, a general decline in prices is visible, although Arabica experiences a slight uptick by 2017. 

![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/4f314b11-3f67-4721-bf7c-156349f0f250)

SOURCE: [(_coffee_prices.ipynb_)](https://github.com/AAlbers341/project1_coffee_analysis/blob/main/EDA/coffee_prices.ipynb)

#### 5.5 Coffee Species Location by Country
The dot map visualizes the global distribution and production output levels of coffee species, with dots sizes indicating production volume and colors distinguishing between Arabica (blue), Robusta (green), and Arabica/Robusta (orange). **The largest bubbles are in South America and South East Asia**, which are regions that have the highest output levels for coffee production. Smaller production volumes are indicated by smaller bubbles in Central America and scattered across Africa. 

![image](https://github.com/AAlbers341/project1_coffee_analysis/assets/137431770/73a07026-cbf4-4aa1-b592-14e45381da7f)

SOURCE: [(_DA Project 1 Presentation_)](https://docs.google.com/presentation/d/12hQMXLd9lk7Ea1zWZkNdEmJW424H0HtRnmNWWuCnCb8/edit#slide=id.g2ad83fcf0fa_0_17)

### 6. Conclusion
Our analysis offers a comprehensive exploration of various aspects of the **coffee** industry and climate phenomena, specifically focusing on coffee production, prices, and the influence of **El Nino and La Nina**. While the insights gained from these analyses are invaluable for understanding the complex dynamics of the **global coffee market** and the interplay between **environmental factors** and agricultural production, the **correlation** between Arabica and Robusta **coffee prices** and the **Oceanic Index** (El Nino and La Nina) suggests that while meteorological conditions may have some impact on coffee prices, they are likely **_not_** the sole influencing factor.
