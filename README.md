I love watching soccer (FC Barcelona fan) and wanted to visualize/analyze some data from some of my favorite players and matches.

The Wirtz ShotMap file utilizes data from the 2023/24 Bundesliga season to map Florian Wirtz's shots - which were goals, which were misses,
  and more, taking into account xG and other important variables. I want to see where Wirtz is more effective, as he a big target for Barça
  as a "marquee signing" in 2026 as presidential elections for the club are coming up. 

The Olmo vs Gundogan heatmap was inspired by Dani Olmo's recent Barça registration. Gundogan left the club to free up financial space
  so Barça had the financial room to register Olmo. The players play the same position (attacking midfield), but I wanted to see their heatmaps 
  in arguably one of the best games of UEFA Euro 2024 where they played against each other. I want to see what space they occupy and what FC Barcelona
  will be gaining and losing with this registration.

The FC Barcelona passmap looks at the team's passing in the UEFA champions league final 2008/09 (arguably the best team of all time)
  I used the networkx package to visualize a network of their passes - the distinct 'tiki taka' (short, quick, successive passes) style.

The LaLiga COVID xT Analysis uses data from the 2020/21 laliga season to create a model for determining expected threat. i use that data to plot a heatmap of the most threatening parts of the pitch. i then made 2 machine learning models
  1: a linear regression model for expected threat, which uses the data to predict the most threatening positions on the pitch.
  2: a logistic regression model that uses the data to predict goal probability.
  2a: i modified the model using Messi's shot data, adding the distance from goal and shot angle. I had to adjust the threshold many times to get the highest possible accuracy, precision, and recall.
