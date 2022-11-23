# Running the jar file:

java -jar  cards.jar

This command will automatically run the CardGame executable class

# To run the test suite

#### The complete test suite that tests all of the classes:

java -cp junit-4.13.2.jar:hamcrest-core-1.3.jar:.  game.CompleteTestSuiteRunner

#### The test suite that only tests the CardDeck related methods:
java -cp junit-4.13.2.jar:hamcrest-core-1.3.jar:.  game.CardDeckTestRunner

#### The test suite that only tests the Game related methods:
java -cp junit-4.13.2.jar:hamcrest-core-1.3.jar:.  game.GameTestRunner

##### The test suite that only tests the Player related methods:
java -cp junit-4.13.2.jar:hamcrest-core-1.3.jar:.  game.PlayerTestRunner
