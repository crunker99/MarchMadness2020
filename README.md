# MarchMadness2020 Tableau Dashbaord

<!-- ### Data Visualization (Tableau Dashboard) of NCAA March Madness Basketball  -->

#### #KCTUG Viz-a-Thon Competition using historical NCAA data.

Jared Keil and Justin Turner teamed up to build a March Madness Dashboard in Tableau to display both predictions and team statistics.

Follow the link below to preview the interactive dashboard:

### [Vizualization](https://public.tableau.com/profile/justin.turner5432#!/vizhome/MarchMadnessBook2/Dashboard1?publish=yes)

Web scraping for official team colors and logos was completed using BeautifulSoup, Urllib, and Requests in Python, and integrated into dashboard.


[Web Scraping Jupyter Notebook](../blob/master/color_logo_scrape.ipynb)

[Colors/Logo Source](https://dynasties.operationsports.com/team-colors.php?sport=ncaa)

### Prediction method

Predictions from Elo win probability formula stood up to machine learning models (XGBoost, Logistic Regression). Process and results viewable in ['Model' Jupyter Notebook](../blob/master/Model.ipynb)

#### Formula: 

![E_a = \frac{1 }{1 + 10^{(R_a - R_b)/400}}](https://render.githubusercontent.com/render/math?math=E_a%20%3D%20%5Cfrac%7B1%20%7D%7B1%20%2B%2010%5E%7B(R_a%20-%20R_b)%2F400%7D%7D)

![R_a](https://render.githubusercontent.com/render/math?math=R_a) = Team A's Elo rating,
![R_b](https://render.githubusercontent.com/render/math?math=R_b) = Team B's Elo rating


