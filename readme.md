# Application: **Pig Dice Game**

##### By Noah Horwitz & Angela Weber

###### _First published 2019-11-06_

## Description:
This project was made as part of a pair-coding project at _[Epicodus](http://www.epicodus.com)_, a vocational school for technology careers, based in Portland, OR. The project is designed to create a website for two players to compete in a dice-game, most well know as Pig Dice.

The fully deployed project is hosted on GH-Pages [HERE](https://nhhor.github.io/pig-dice-refactor).

## Setup/Installation instructions:
* Click the `Clone or download` button and copy the link.
* Open your terminal application (assuming GIT Scripts have been installed on your system) and type `git clone (link)`.
* Double click on newly created "portfolio" folder.
* Double click on "index.html" to open the file in the web browser of your choosing.

## Technologies Used
> `HTML`
> `CSS`
> `Bootstrap`
> `JavaScript`
> `jQuery`

## Known Bugs
* None

## Specifications

|Spec|Input|Output|
|-|-|-|
|Upon clicking `[Roll again]`, a random number (between 1 and 6) will be calculated, displayed, and appended to a turn-total summand.|`[Roll again!]`|3|
|On a given player's turn, should they roll a 1, their turn-total will revert to 0 and their turn will be over.|`[Roll again!]` 1|"You rolled a 1", next player's turn.|
|On their turn should either player click `[HOLD!]` after any number of non-1 rolls, their turn-total will be added to their total game score and it will be the next player's turn.|2,5,3,6,4,`[HOLD!]`|Score: 20|
|The first player to reach a total score of 100 will win the game.|Player One starting score: 93. `[Roll again!]` 6, `[Roll again!]` 2, `[HOLD!]`|"Score: 101" & "Player 'x' Wins!"|



## References
* None

## Support and contact details
Contact [example@sample.com](mailto:example@sample.com)

## License
_This This repository is copyright (C) 2019 by Noah Horwitz & Angela Weber and is licensed under the GNU General Public License v3.0 [gpl-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)_.
