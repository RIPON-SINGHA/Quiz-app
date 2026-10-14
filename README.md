# Quiz App

A timed quiz app made with HTML, CSS and vanilla JavaScript. Questions come from the Open Trivia DB API.

Live demo: YOUR-LIVE-LINK-HERE

## Features

- Choose a category and a difficulty (easy, medium, hard)
- 10 multiple choice questions per game, options shuffled
- 15 second timer for each question with a progress bar
- Correct and wrong answers are highlighted after you submit
- Result screen with score, correct / wrong / timed out count, and a review of the questions you missed
- Scoreboard with your top 10 scores, saved in localStorage
- Play again or change category from the result screen

## Built with

- HTML, CSS, JavaScript (no frameworks)
- Fetch API with async/await
- localStorage
- Open Trivia DB API
- Font Awesome (CDN)

## Run it

Download or clone the repo and open `index.html` in a browser. You need internet for the questions to load.

## Files

- `index.html` - the four screens (select, quiz, result, scoreboard)
- `style.css` - styling
- `app.js` - all the logic

## Credits

Questions from [Open Trivia DB](https://opentdb.com/).