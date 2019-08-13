# NBA Elo System
A NBA Elo Rating System. 

View at: https://sjellard.github.io/ELO-NBA/

View Jupyter Notebook at: https://nbviewer.jupyter.org/github/SJEllard/ELO-NBA/blob/master/ELO-NBA-jupyter.ipynb

<h2>Description</h2>
NBA Elo System is an inferential rating system that calculates the relative strength of NBA teams. 

A teams strength is represented by their rating (the higher, the better). 
After every game, the winner takes points from the loser. 

The amount of points won (or lost) is determined by the difference in ratings. 
For example, when a high rated team beats a low rated team they will only win a few points.
But, when a low rated team upsets a high rated team, they win many points. 

This project has been significantly inspired by Nate Silver’s statistical NBA projections. To see more of Nate Silver’s work visit <a href="https://projects.fivethirtyeight.com/complete-history-of-the-nba/#raptors" target="_blank">The Complete History of the NBA</a> and <a href="https://fivethirtyeight.com/features/how-we-calculate-nba-elo-ratings/" target="_blank">How We Calculate NBA Elo Ratings</a>.

To learn more about Elo rating systems visit the <a href="https://en.wikipedia.org/wiki/Elo_rating_system" target="_blank">Elo Wikipedia page</a>.

<h2>How to Use</h2>
Instructions will go here

<h2>Technologies Used</h2>
NBA Elo is written in Python using Pandas and Jupyter Notebook. 

Plot.ly is used for graphs. 

<h2>Planned Updates</h2>
<li>Implement homecourt advantage
<li>Decrease autocorrelation (Lower K Value)