# JavaSpider #
This is our 23 Code Street project

JavaSpider is a game to test you on your JavaScript knowledge - combining elements of a canvas game and online quiz.

Catch the spider and see if you can answer all the questions!

[Play the game!](https://kittaru87.github.io/JavaSpider/)

**Languages used:** HTML, CSS, JavaScript

## Files ##
* **Index.html** = Home page of JavaSpider, featuring instructions on how to play the game, leading to...
* **webcanvasindex.html** = Spider and fly game: once the spider eats the fly it opens up a quiz game
* **Index-answer.html** = First page of the quiz game, features 5 questions to answer and outputs a score
* **Index-answer-page2.html** = Second page of the quiz game, features 5 questions to answer and outputs a score
* **main js** = Contains js functions of the game, including spider movements, collision detection, scoreboard and calling of the canvas

### Background ###
Our team was tasked with planning, designing and building a game that featured elements of HTML, CSS and JavaScript. We had all enjoyed the class where we created a canvas game with a moveable sprite so wanted to incorporate that idea as much as possible. We also decided that an educational game would be helpful to other students learning JavaScript (a language we all found challenging), and so JavaSpider was born!

We brainstormed ideas of how we wanted the game to look, what possible levels there were and what the goal of the game was. With only a week and a half to build our game we decided upon a simple sprite based canvas game that would randomize the location of the fly that the spider was to catch, and which would then lead onto a quiz. 

### Alternative ideas ###
We had so many ideas. But time was tight and we couldn't attempt all of them. 
- **Pop up to feature the quiz (or keep the quiz on the same page)**: With time constraints and a limited knowledge of the vagaries of Github and Fork we decided it would be simpler to give people different jobs to do on different pages. However had we kept the quiz on the same page, the scoreboard feature would probably work. Something to consider.
- **Enemies**: We didn't want our spider to have too easy a life and hoped to include a random moving enemy (probably some form of fly swatter) that would pace around the canvas. When you got swatted either you would die and the game would end or you'd lose some points.
- **Animation**: A bit like the the spider on the home page we would have liked to animate the features on the board (maybe the fly would shake, or the spider would use his web to move around a bit quicker).
- **More quiz questions**: We would have liked to have done more pages but time was not on our side.

### Known bugs ###
* Second quiz page not loading - the game should cycle between the two quiz games (this has worked before)
* Sound effect of the spider eating the fly doesn't load consistently
* Scoreboard resets to 0 when the spider canvas reloads. Ideally it would bring the score from the quiz game across - possibly via the use of cookies. It does work for a split section before the quiz page loads.
* We didn't have enough time to add any resources into the resource section of the quiz.
