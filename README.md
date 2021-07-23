# Premier_League_Regression_Project
Explorative Regression Analysis of 2018-19 Premier League Season

Context
In many sports, like Tennis, Golf, Basketball, and American Football, the repercussions of poor performance can be detrimental. However, in comparison to Football, the implications of poor performance can have a more lasting effect on the future of football teams.
In the majority of football leagues across the world, when a team is consistently poor throughout the season they tend to finish lower in a lower league position, and can even be relegated. This has severe implications on clubs relating to; finance, eligibility to play in continental competitions, and the players they can attract. Especially when considering relegation, even some of the biggest clubs can struggle to return to the topflight. For example, after relegation, Leeds spent 16 years trying to return to the Premier League.
The Covid-19 pandemic has made the financial sustainability of football clubs even more critical, due to a reduction in revenue from match attendances(COVID-19, Football & Digital: 2020/21 Season & Beyond, 2021). Furthermore, the implications of poor performance have become even more severe. Hence why identifying the specific pitch actions that are associated with team success is crucial.

Challenges of analysing football performance
In the past, performance analysis has focused on American Sports such as; Basketball, American football, and Baseball. This is primarily because American sports can easily be separated into distinct actions by stoppages in play, for example, through the use of timeouts. Conversely, football is a game intended to be fluid, with a continuous flow of attack and defence usually mirroring fans' emotions. Typically, Fans' reactions to the introduction of VAR have supported this view. Many believe it inhibits the rush of emotions throughout a game by breaking it up, and subsequently 'ruining the beautiful game'.
The key challenge when attempting to analyse team success within football relates to its multifaceted and complex nature. Both technical and physical indicators have been used to predict team success by numerous studies(Collet, 2013; Impellizzeri et al., 2008; Lago-Peñas, Lago-Ballesteros and Rey, 2011).
Physical performance characteristics such as distance covered etc. impact team success indirectly through their effect on technical proficiency(Rampinini et al., 2008). Conversely, several technical indicators are associated with team success, including; number of passes, pass completion(%), possession(%), number of shots, shots on target, total crosses, yellow cards, %Goals to shots and average goals conceded. (Collet, 2013; Lago-Peñas, Lago-Ballesteros and Rey, 2011; Oberstone 2009).
In the past studies have utilised a reductive approach and focused on isolating physical or technical indicators, analysing them across a season(Oberstone, 2009). In using this approach, the varied and complex nature of actions on a football pitch can be broken down into smaller parts, and their association with team success can be investigated. Although a limitation of the approach is that its based on the assumption that the whole technical performance is simply a sum of the isolated elements (Mclean et al. 2017). Therefore not taking into account how tactical or physical pitch actions may have affected performance.

### What I intended to do with the data 

1. I intended to analyse each segment of data relating to general pitch actions such as possession, passing, shooting, defence, and goalkeeping to identify the specific pitch actions of each general pitch action that are most associated with points obtained.

2. Eliminate redundant predictor variables based on collinearity, e.g. variables that explain the same element, number of shots on target and the total number of shots made are explaining the same effect that % of shots on target are 

3. Test if the variables meet the assumptions for multiple linear regression  

5. Run the appropriate regression model 

6. Test the accuracy of the model by plotting the predicted points vs the actual points. 

7. Compare the features selected for the model with previous studies
