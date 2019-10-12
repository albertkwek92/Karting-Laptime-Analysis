# Karting-Laptime-Analysis

I visit Traxx Raceway very often, and was always interested to track my performance at the race track. As such, I used to manually key in lap times into an excel sheet after each session and it took a lot of time and was not scalable. So, I decided to use the BeautifulSoup library to help webscrap my laptimes obtained at Traxx. The initial intent of this was to plot a graph of my progression, but I ventured into further analysis such as whether a different kart number had an impact on my performance etc. So this jupyter notebook file does the following:

1) Scrap laptime data
2) Perform ANOVA 2 way analysis to determine if kart number affects performance
3) Draw a graph to illustrate the best laptime progressions from my sessions
