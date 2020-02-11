# JavaSpider #
This is our 23 Code Street project

JavaSpider is a game to test you on your JavaScript knowledge - combining elements of an 8-bit game and online quiz.

Catch the spider and see if you can answer all the questions!

[Play the game!](https://kittaru87.github.io/JavaSpider/)

## Files ##
* **Index.html** = Home page of JavaSpider, featuring instructions on how to play the game, leading to...
* **webcanvasindex.html** = Spider and fly game: once the spider eats the fly it opens up a quiz game
* **Index-answer.html** = First page of the quiz game, features 5 questions to answer and outputs a score
* **Index-answer-page2.html** = Second page of the quiz game, features 5 questions to answer and outputs a score
* **main js** = Contains js functions of the game, including spider movements, collision detection, scoreboard and calling of the canvas

### Known bugs ###
* Second quiz page not loading - the game should cycle between the two quiz games (this has worked before)
* Sound effect of the spider eating the fly doesn't load consistently
* Scoreboard resets to 0 when the spider canvas reloads. Ideally it would bring the score from the quiz game across - possibly via the use of cookies.
