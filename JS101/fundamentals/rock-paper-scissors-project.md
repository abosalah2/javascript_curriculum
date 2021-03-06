We're going to make a simple implementation of grade-school classic "rock paper scissors".  If you don't know what that is check the [wikipedia article](https://en.wikipedia.org/wiki/Rock%E2%80%93paper%E2%80%93scissors) or [this](https://www.wikihow.com/Play-Rock,-Paper,-Scissors) ridiculous step-by-step.  For the moment we're just going to play the game from the browser console, but we will revisit it and add a front end later so don't forget to keep the code on GitHub! 

## Your assignment

1. Start a new git repo for your project.
2. Create a blank HTML document with a script tag.  This game is going to be "played
   " completely from the console, so don't worry about putting anything else in there.
3. Your game is going to play against the computer, so begin with a function called `computer_play` that will randomly return either 'Rock', 'Paper' or 'Scissors'.  We'll use this function in the game to make the computer's play.
4. Write a function that plays a single round of Rock Paper Scissors.  The function should take a string 'Rock', 'Paper' or 'Scissors' as a parameter, should call the `computer_play` function and then return a string that declares the winner of the round like so: `"You Lose! Paper beats Rock"`
   1. If the input is NOT an appropriate option, return a message that says `"Invalid input"`
   2. make your function case insensitive (so users can input `rock`, `ROCK`, `RocK` or any other variation)
5. Expand on the previous function by writing a NEW function called `game()`.  Use the previous function _inside_ of this one to play a 5 round game that keeps score and reports a winner or loser at the end.
   1. At this point you should still just be using `console.log()` to display the results of each round and the winner at the end.
   2. use `prompt()` to get input from the user. [Read the docs here if you need to.](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt)
   3. Feel free to re-work your previous functions if you need to.  Specifically, you might want to change the return value to something more useful.
   4. Feel free to create more "helper" functions if you think it would be useful.

## Student Solutions

Send us your solution so we can show others! Submit a link to the Github repo with your files in it by using any of the methods listed on the contributing page.  See the Google Homepage project for examples.

- Add your solution below this line!