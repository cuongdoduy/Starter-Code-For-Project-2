# Project Overview
You have been given a list of teams and players. You've been tasked with cleaning up the player data and then organizing the players into equal teams for the upcoming basketball season.

You will apply your knowledge of built-in Python data types and combine these types to create structures to store and organize a team of Basketball players into distributed teams. This tool will not only balance the teams by the total number of players but also let you generate some statistics for a given team.

# Basketball Team Stats Tool
In this project you will be writing a program that reads from the "constants" data (`PLAYERS` and `TEAMS`) in `constants.py`. This data will need to be translated into a new collection of your choosing and the fields need to be changed to something that makes more sense for Python to do its comparisons.


**NOTE**: Python has no concept of actual constants like some other languages out there. But it is a convention in Python to treat ALL CAPS variables as if they are in-fact constants.


**Steps to get started:**

1. Create a new empty script file called `app.py` or `application.py`


2. Import player and team data

   Import from constants.py the players and team data to be used within your program. Players and Teams should not be hard-coded in our script. If a team name or player name changes in constants.py, it should be reflected when we run our app.


3. Create a clean_data function

   Write the logic to:
   + read the existing player data from the PLAYERS constants provided in constants.py 
   + clean the player data without changing the original data (see note below) 
   + save it to a new collection - build a new collection with what you have learned up to this point.

   Require:
   Height: This should be saved as an integer
   Experience: This should be saved as a boolean value (True or False)
   Guardian: Clean the guardian field as well before adding it into your newly created collection, split up the guardian string into a List. NOTE: There can be more than one guardian, indicated by the " and " between their names.


4. Create a balance_teams function

   Now that the player data has been cleaned, balance the players across the three teams: Panthers, Bandits and Warriors. Make sure the teams have the same number of total players on them when your team balancing function has finished.
   Displaying the stats


5. When displaying the selected teams' stats on the screen you will want to include:

   Team's name as a string
   Total players on that team as an integer
   The player names as strings separated by commas
   number of inexperienced players on that team
   number of experienced players on that team
   the average height of the team
   the guardians of all the players on that team (as a comma-separated string)

## Advance
1. Additional balancing to the team

   Additionally, balance the teams so that each team has the same number of experienced vs. inexperienced players.
   If this is done correctly each team stats should display the same number count for experienced total and inexperienced total as well as the same total number of players on the team.


2. Quit Menu Option

   The user should be re-prompted with the main menu until they decide to "Quit the program". 


3. Organize Players by Height

   When printing the players to the console, print them out from the shortest to the tallest player.


4. Save the Team’s Analysis

   Save the following data points to the team’s data structure:
   number of inexperienced players on that team
   number of experienced players on that team
   the average height of the team
   
### If you get stuck, try to work through the problem. Sometimes it helps to try to write/draw out your steps on paper in the order your program should run in and solve each step 1 at a time. If you are still stuck be sure to reach out in the Slack channel.

