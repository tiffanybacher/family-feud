## Table of contents
* [Intro](#Family-Feud-Game-App)
* [Screenshots](#Screenshots)
* [Getting Started](#Getting-Started)
* [How to Play](#How-to-Play)
* [Project Emphasis](#Project-Emphasis)
* [License](#License)

# Family Feud Game App

This project is a Turing front-end evelopment project focused on working with ES6 classes and existing datasets.

This is a two player game modeled after the TV show ‘Family Feud’.  Each game has three rounds, and in each round there is a question that has three top survey responses. The two players take turns guessing the answers until they are all guessed and their score increments by the number of respondents who submitted that guess.  The third round is a special round where each player gets their own question and 30 seconds to guess as many times as they like, and the score of correct guesses is doubled for that round.


## Screenshots

![Player name entry](/screenshots/familyfeud1.png)
![Round 1 gameplay](/screenshots/familyfeud3.png)
![Round 2 gameplay](/screenshots/familyfeud2.png)
![Round 3- Fast Money round with timer](/screenshots/familyfeud4.png)
![Winner display with play again option](/screenshots/familyfeud5.png)


## Getting Started

### View Live on GitHub

You can view the game live on my GitHub at the following link:

<a href="https://lynnerang.github.io/family-feud/">Family Feud Game App - Live!</a>

### Get Your Own Copy

If you'd like to clone this repository to your own local machine, run the following command in your terminal:

```shell
git clone https://github.com/lynnerang/family-feud.git
```

Then run the following command to install dependencies:

```shell
npm install
```

To view the app in action, run the following command in your terminal:

```bash
npm start
```

Then, go to `http://localhost:8080/` in your browser to see the code running in the browser.

---

## How to Play

1. Both players enter their names and click "Start New Game".
2. Round 1 begins, and a question is displayed on the board.
3. Player 1 goes first and the players take turns guessing top survey responses for the question.
4. If a player answers correctly, they get to guess again.  If not, it's the other player's turn.
5. When a correct answer is guessed, the player who guessed it has their score increased by the number of respondents for that answer.
6. When all three answers are guessed, the game moves to the next round.
7. When the players reach Round 3, a special "Fast Money Round" starts.  They each get a question with 30 seconds to guess as many times as they like.  The scores for correct guesses are doubled for the round.
8. The game will end after Round 3, and the winner is the player with the highest total score.


## Project Emphasis

View the project specification (user stories & other requirements) on the <a href="http://frontend.turing.io/projects/module-2/family-feud">Turing webpage for this project</a>.

- [x] HTML & CSS 
- [x] Flex-box
- [x] UI design
- [x] jQuery
- [x] Es6 classes
- [x] Working with existing datasets
- [x] Mocha & Chai testing
- [x] Webpack
- [x] NPM
- [x] ESLint


## Licensing

All credit goes to <a href="turing.io">Turing School of Software</a> for providing the project specifications.
