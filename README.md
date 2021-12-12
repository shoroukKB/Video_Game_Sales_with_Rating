# Video_Game_Sales_with_Rating

# Problem definition
This project reviews a set of video game sales data rated by the ESRB for the purpose of monitoring and age-appropriate game content. The ESRB is officially recognized, implemented and used in the three main countries of North America: Canada, Mexico, and the United States. The Ai model will be built to predict the appropriate age rating for each game based on the data collected.

# Data Description
 | Feature       | Description                                                                                                                                           |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| Name          | Name of the game                                                                                                                                      |
| Platform      | Console on which the game is running                                                                                                                  |
| YearofRelease | Year of the game released                                                                                                                             |
| Genre         | Game's category                                                                                                                                       |
| Publisher     | Game publisher                                                                                                                                        |
| NASales       | Game sales in North America (in millions of units)                                                                                                    |
| EUSales       | Game sales in the European Union (in millions of units)                                                                                               |
| JPSales       | Game sales in Japan (in millions of units)                                                                                                            |
| OtherSales    | Game sales in the rest of the world, i.e. Africa, Asia excluding Japan, Australia, Europe excluding the E.U. and South America (in millions of units) |
| Global_Sales  | Total sales in the world (in millions of units)                                                                                                       |
| Critic_score  | Aggregate score compiled by Metacritic staff                                                                                                          |
| Criticcount   | The number of critics used in coming up with the Criticscore                                                                                          |
| User_score    | Score by Metacritic's subscribers                                                                                                                     |
| Usercount     | Number of users who gave the userscore                                                                                                                |
| Developer     | Party responsible for creating the game                                                                                                               |
| Rating        | The ESRB ratings                                                                                                                                      |

* To get the data sorce click [here](https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings)
* Target feature is Rating

# Question and need
 What is the framing question of your analysis, or the purpose of the model/system you plan to build?
  * Bulding a model that predict the rating of the game.
  * Find the most important features that effect the predection.
  * Find the least important features that effect the predection.
  
 Who benefits from exploring this question or building this model/system?
  * Governments to Help steer children from games with inappropriate content.

# Tools
Jupyter notebook libraries:
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Plotly
* NumPy 


Machine learining algorithm:
* Logistic regression

# Contact info
* Email: shuruq.batrah@gmail.com
