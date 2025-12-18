# Number of Breweries in the United States 2014 - 2024
## Alex Miramontes
* [GitHub](https://github.com/miramontron)
* [Linkedin](https://www.linkedin.com/in/alexmiramontes/)

## Purpose
This project investigates trends in production in the U.S. beer industry between 2014 and 2024. The goal is to determine how the number of breweries and their production volume may have changed in the wake of the COVID pandemic. 

## Research Objectives

1. **Primary Question:** How has the number of breweries operating in the United States changed over the last ten years? The beer industry experienced an explosion of new breweries thanks to the popularity of craft beer; this question examines if those growth trends have continued.
2. **Secondary Question:**  How has the volume of beer produced changed in the years following the COVID pandemic? The COVID pandemic changed many facets of our lives from how we gather together to what we prioritize in our spending habits. Looking at the growth explorations from my primary question I want to use 2020 as a benchmark for pre and post pandemic trends in the volume of beer produced. 
3. **Exploratory Question:** Have breweries at smaller scale grown more than their larger counterparts? Smaller breweries have a lot of advantages over their larger counterparts: fresher product; more nimble responses to market trends; better sentiment from the community, but do those advantages translate compared to larger breweries that can produce significantly more product for lower costs? 

## Data
* [Brewers Association - Brewery Production](https://www.brewersassociation.org/category/insights/)
* [U.S. Department of the Treasury: Alcohol and Tobacco Tax and Trade Bureau](https://www.ttb.gov/beer/statistics)
    * Monthly Beer National Report
    * Number of Brewers by State
    * Number of Brewers by Production Size

## Tools Used
* [Python](https://www.python.org)
* [pandas](https://pandas.pydata.org)
* [Matplotlib](https://matplotlib.org)
* [Plotly Express](https://plotly.com/python/plotly-express/)
* [LucidChart](https://www.lucidchart.com/pages)
## Getting started

To replicate this project:

1. Clone the repository:
```
git clone https://github.com/miramontron/number_of_us_breweries.git
```

2. Create and activate a virtual environment, and install required packages from `requirements.txt`:
* Linux/macOS:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
* Windows:
```
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
```
3. To deactivate:

```deactivate```

## Conclusions

* The overall number of breweries continued to rise in the years following the 2020 COVID pandemic. 
* The number of breweries licensed by the TTB, but not producing beer, has steadily climbed over time but the trend leveled off after 2021 before beginning to decline in 2023.
* The number of breweries producing >0 to 1,000 barrels greatly climbed in the years prior to 2020.
* The number of breweries producing >1,000 to 7,000 barrels was steadily climbing before beginning to decline in 2019, coming back up to prior highs, and beginning another decline.
* The number of breweries producing beyond 7,000 barrels largely stayed the same.
* Over the course of the period of time examined craft beer made only marginal gains in market share, while Imports nearly doubled their share.
* In 2024 every state in the United States had several breweries, but there's a marked difference between the states with the most breweries (California: 1,624 breweries) and the fewest breweries (North Dakota: 33).

## Colophon

### Resources
* [From Data to Viz](https://www.data-to-viz.com/#explore)
* [Viz Palette](https://projects.susielu.com/viz-palette)
* [Daytum](https://daytum.com)

### AI Disclosure
AI was used in this project in the form of search engine assist. 