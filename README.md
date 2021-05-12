# Tic Tac Toe game

![screenshot](./readme_lib/Tic-tac-toe-animated.gif)

This is a simplified Tic-Tac-Toe game for two players, powered by ruby and displayed in Terminal.
The concept is simple. There's a 3x3 grid with empty spaces waiting for the players to fill them with their tokens (X or O). You compete against your opponent to fill a line of three vertical, horizontal, or even diagonal spaces inside the grid. The first to do it wins. If no player gets to build the line of three, it's a draw. Have fun!

## Tic-Tac-Toe for Dummies

This is a handbook of this game's flow and usage, so that you don't get lost.

First of all, introduce yourselves! The console will ask your names in order both players.
By standard, Player one uses X as a token, and Player 2 uses O instead. Keep this in mind

Now you are ready to start playing. You two will take turns placing tokens in the board. The required input is a number between 1 and 9; these represent the spaces in the board. Please don't bother the computer giving it letters or the number of a taken spot, or it may turn against you some day...

Anyways. If any of you manages to build a straight line of your tokens in any direction, congratulations! You won!
Restart the game by running 'bin/main.rb' to play again. It's highly suggested that you take turns with your opponent playing first, or they'll hate you for life.

You can stop running the game at any point with the ```Ctrl C``` key combination. You might need to also give a value and press enter at some points of the code before exiting. This is a fashionable way of rage-quitting.

Good luck and have fun playing Tic Tac Toe!

## Built With

- Languages used
  - Ruby
- Other tech
  - Ruby compiler
  - VS Code
  - Git Bash and GitHub


## Getting Started

To get a local copy up and run the program do this steps on the console:
- To clone the project to your machine, run `git clone https://github.com/petumazo/Tic-Tac-Toe.git`
- To navigate in to the project folder/directory, run `cd Tick_Tack_Toe/bin`.
- To run the executable creator, run 'gem install ocra' and then 'ocra main.rb'
- To go back one folder run 'cd ..'
- To install the required dependencies, run `bundle install`
- To run the game, run `bin/main.rb` in the console.

### Prerequisites
- Have ruby compiler installed on your system. You can get it from [here](https://www.ruby-lang.org/es/documentation/installation/)

## Running tests with Rspec

This game is tested with Rspec(domain-specific language (DSL)) testing tool written in Ruby programming language to test Ruby code. It is a behavior-driven development (BDD) framework which is extensively used in production applications.

## How to get Rspec running

- Open the terminal, type `gem install rspec`
- Once rspec installed, you can check for the version using 'rspec --version' 
- Go to project directory and type `rspec --init` to initialize the rspec in your project
- You will see a folder `spec` and a file `.rspec`
- Inside spec folder you'll see a `spec_helper.rb` file.
- Create your spec files in the spec folder.
- In the terminal, type `rspec` to run the spec file

## Rspec output
![screenshot rspec](./screenshots/rspec.png)

## Authors

👤 **David Alvarez**

- GitHub: [@petumazo](https://github.com/petumazo)
- Twitter: [@petudeveloper](https://twitter.com/petudeveloper)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/david-alvarez-mazzo-777712143/)

👤 **Julian Carracedo**

- GitHub: [@JuliCarracedo](https://github.com/JuliCarracedo)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/julian-carracedo-0b8518207/)

👤Fondem Junior
 - [Github](https://github.com/Fondem-Jr)
 - [Linkedin](https://www.linkedin.com/in/fondem-junior-57484744/)
 - [Twitter](https://twitter.com/OpportunistZeus)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## Show your support

Give a ⭐️ if you like this project!
