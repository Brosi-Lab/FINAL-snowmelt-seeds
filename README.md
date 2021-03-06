# FINAL-snowmelt-seeds

Analysis by Xingwen Loy and Berry Brosi

In this analysis, we assess if the timing of snowmelt impacts seed set in montane plant communities, with a plant-community-level focus. We conducted an accelerated snowmelt experiment at RMBL, Colorado in summer 2019. We worked at 8 sites scattered across 2 valleys. In each site, we had paired control and snowmelt acceleration plots, each 14 x 10 m (thus there were 16 plots total). We accelerated snowmelt by solarizing the snow with black shade cloth, which was removed just before snow melted to ground level. Snowmelt rate in control plots was unmanipulated. In many plant species, accelerating snowmelt caused earlier plant flowering relative to controls. We hypothesize that earlier snowmelt date could affect plant seed set through advances in flowering time that potentiate plant-pollinator phenology mismatches.

The simplest way to get a feel for the analysis is to look at the .html report of the analysis, generated by our Rmarkdown analysis file. The report covers the entire breadth of our analysis including data import, data cleaning / formatting, statistical models, model assessment, and plots. The design of the report is focused on human readability.

File structure:

* **main folder** contains:
    + R project file ("FINAL-snowmelt-seeds.Rproj")
    + Rmarkdown file ("Final Seed Analysis RMBL2019.Rmd")
    + Rmarkdown html report ("Final Seed Analysis RMBL2019.html")
* **data subfolder** contains the 3 input data files:
    + "Masterseed2019.csv" (contains all seed production data and most of the other data used)
    + "regressionmeltdays.csv" (data on snowmelt patterns in snowmelt-accelerated relative to control plots)
    + "phenoshifted.csv" (data on flowering phenology shifts in snowmelt-accelerated relative to control plots)
* **results subfolder** contains 2 tables with model results from the first two of three primary models (the third has only a single line of results)
* **plots subfolder** has saved plots from the analysis
    
