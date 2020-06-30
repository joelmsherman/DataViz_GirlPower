# DataViz-GirlPower

Objective:  Reimagine and recreate the Woman, Business and the Law Data Visualization of Gender Equality
https://data.world/makeovermonday/2020w26/workspace/file?filename=Economic+Empowerement.png

Data Source:  World Bank WBL
https://wbl.worldbank.org/en/wbl-data

Original Chart: joelmsherman/DataViz_GirlPower/EconomicEmpowerment.png
Revised Chart: joelmsherman/DataViz_GirlPower/Dashboard1.pdf

Methods:  Review all Women, Business and the Law (WBL) documentation and data.  Download data as Excel and read into Tableau.  Create Fixed level of detail measure for average equality index score:  AVG({FIXED [Country], [WBL Report Year], [Question Category]: SUM([Index Score])}). Create global MapBox theme map on score by year.  Create indicator-based scores by year, with filter action based on map country selection.  
