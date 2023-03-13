# Othello

Web-based game [Othello/Reversi](https://en.wikipedia.org/wiki/Reversi) implemented by HTML, CSS, Vanilla JavaScript

<br>
<div align="center">
  <a href="https://duckbankbok.github.io/othello/" target="_blank"><img src="https://user-images.githubusercontent.com/64826387/222368967-f96a4074-502b-454c-b593-cfb252b2d300.gif" alt="Othello" style="width:400px;height:600px"></a>
</div>

## Rule

* Place four black and white stones in the middle of the 8X8 grid.
* The stone can be placed only where it can surround the opponent's stone(s) in an eight-pronged direction.
* If there is no place to put the stone, the turn passes to the opponent.
* (Additional rule) At the start of the game, 5 spaces are randomly selected where no one can place a stone.
* The game ends in the following cases and the player with more stones wins.

  * When all 59 grids are filled with stones
  * If one side flips all of the opponent's stones
  * If neither side has anywhere to flip the stone

## Development Progress

* v1 : Both black and white are controlled by the player.
* v1.1 (Present): Add draw at start.

  * Goal for next version: Implementing 'player vs. AI' function

## References

* [https://www.youtube.com/watch?v=-ATbKu_0VVs&list=PLA7VQFdAJ2vfytZFoskFIBYLlNuCUGi0N](https://www.youtube.com/watch?v=-ATbKu_0VVs&list=PLA7VQFdAJ2vfytZFoskFIBYLlNuCUGi0N)
* [https://kana.github.io/othello-js/](https://kana.github.io/othello-js/)
* [https://maplestory.nexon.com/News/Event/400](https://maplestory.nexon.com/News/Event/400)
