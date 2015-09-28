# Poker Project

Link to repo ```https://github.com/zach-chai/pok3r```

## Installation
* Install maven ```http://maven.apache.org/```
* Clone the repo ```git clone git@github.com:zach-chai/pok3r.git poker```
* Enter directory ```cd poker```
* Run tests ```mvn test```
* Build a runnable jar ```mvn assembly:single```
* Execute ```java -jar target/poker_ranking-1.0.0-jar-with-dependencies.jar```

Alternatively
* Install Eclipse ```https://eclipse.org/```
* Clone the repo to your workspace ```git clone git@github.com:zach-chai/pok3r.git poker```
* Import as maven project
* From Eclipse you can
 * Execute the JUnit tests
 * Run Game.java to start Game

Alternatively
* If you would like to just run the game there is a built jar under releases
* You can run it with the same command ```java -jar poker_ranking-1.0.0-jar-with-dependencies.jar```


### Playing Instructions
* First input is the number of players
* Next you need to enter the hands for each player id followed by cards. Example ```0 AceHearts NineClubs FiveClubs JackDiamonds EightSpades```
* Once you entered a hand for each player it will calculate the ranks and output them

### Traceability
* Each Class's tests are in a file suffixed with the word test, tests for ```Card.java``` are in ```CardTest.java```.
* Tests for Top level Game flow are in RoundTest.java
* Tests for determining the hands (Flush, Straight, etc) of Cards are in RankGeneratorTest.java
* Tests for constructing cards from text are in CardTest.java
* Many other tests in the test folder for various functions



