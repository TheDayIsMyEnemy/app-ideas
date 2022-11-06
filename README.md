# A collection of application ideas :boom:

<br />

# Projects  :mag:

## Questionnaire  
<p> Create a dynamic questionnaire based on a list of questions provided </p>

The structure of the questions are as follows:  
  * The questions are n-tiered and subsequent questions are asked based on the responses 
    or series of responses of previous questions.
* In general, the questions are grouped, such that a set of questions are asked and that
determines if additional questions need to be added. Similar to the structure of a
treenode, where more questions are revealed if a node is clicked.
*  The questions need to be asked one at a time
*  The responses to the questions can be Boolean, radio selection (Boolean can fit here),
checkbox selection, checkbox selection with “other” textbox, or informational textbox.
*  Each question is assigned a “point” value, and this needs to be recorded and reported to
tabulate a response
*  from the Analyst – this point value is typically used to discretionary display further
questions depending on the value reported.
* The initial question (tier 0) is the acceptance of a disclaimer.
*  There are domains for the sets of questions (aka categories) and this does not need to be
displayed

## Synonyms game  
https://wordnet.princeton.edu/  
https://dictionaryapi.dev/  
https://developer.oxforddictionaries.com/documentation  

## Blazor WebAssembly game  
https://github.com/amolenk/GameATron4000   
https://github.com/fernandreu/blazor-pages  

## Contribution graph pixel art
### Requiremenets  
* Trigger a workflow
* Calculate a recurring event
* Push a commit

### References
* https://github.com/gelstudios/gitfiti  

## News feed profile readme  
### Requirements  
* Specify topics, keywords and time interval to trigger an action
* GitHub Actions
  * [Events that triggers workflows](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows)
* Fetch and filter data 
* Update profile readme 

## Sports betting bot  
### Requirements  
* Sports Database
  * Types of Sports games
    * Football
      * club, league, country
      * club statistics: wins, losses, touches, own goals, yellow cards, red cards, goals,
      passes, shots, offsides, hit woodwork, big chances missed, tackles, clearances,
      clearances off line, dispossessed, clean sheets, saves, penalties saved, high claims, punches
      * season ?
      * players: club, nationality, position
      * player position: Goalkeeper, Defender, Midfielder, Forward
      * league player statistics: goals, assists, clean sheets, appearances, minutes played, yellow cards,
      passes, touches, shots, hit woodwork, big chances missed, tackles ( stats is saved by season for comparison )
  * Game results ( datetime, teams, score, odds )
  * Game rules for calculating winning conditions?
  
* Log In 
  * by using Selenium or any other other tool
  * by using a list of user credentials for each website
  
* Data Scraping
  * odds from selected bookmakers 
  * news about sports games
  * history for a game, player or any other related data
  
* Arbitrage
  * Checks betting odds for a certain event and automatically calculate whether an arbitrage bet is possible

### References  
https://en.wikipedia.org/wiki/Arbitrage_betting  
https://github.com/georgedouzas/sports-betting    
https://www.premierleague.com/stats/top/players/goals?se=489  
https://data.world/datasets/sports  
https://datahub.io/collections/football
