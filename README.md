# Super-Bowl-Exploratory-Analysis
In this notebook, I have performed Exploratory Analysis of Super Bowl dataset by loading, cleaning, then exploring Super Bowl game, television, and halftime show data. I have visualized the distributions of combined points, point differences, and halftime show performances using histograms. Also, there was line plots usage to see how ad cost increases lagged behind viewership increases. 

# Introduction

Whether or not you like football, the Super Bowl is a spectacle. There's a little something for everyone at your Super Bowl party. Drama in the form of blowouts, comebacks, and controversy for the sports fan. There are the ridiculously expensive ads, some hilarious, others gut-wrenching, thought-provoking, and weird. The half-time shows with the biggest musicians in the world, sometimes [riding giant mechanical tigers](https://youtu.be/ZD1QrIe--_Y?t=14) or [leaping from the roof of the stadium](https://youtu.be/mjrdywp5nyE?t=62).  And in this notebook, we're going to find out how some of the elements of this show interact with each other. After exploring and cleaning our data a little, we're going to answer questions like:

- What are the most extreme game outcomes?
- How does the game affect television viewership?
- How have viewership, TV ratings, and ad cost evolved over time?
- Who are the most prolific musicians in terms of halftime show performances?


The dataset we'll use was [scraped](https://en.wikipedia.org/wiki/Web_scraping) and polished from Wikipedia. It is made up of three CSV files, one with [game data](https://en.wikipedia.org/wiki/List_of_Super_Bowl_champions) one with [TV data](https://en.wikipedia.org/wiki/Super_Bowl_television_ratings), and one with [halftime musician data](https://en.wikipedia.org/wiki/List_of_Super_Bowl_halftime_shows) for all 52 Super Bowls through 2018. 
