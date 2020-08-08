# Busca Minas

### Links

---

[Repositorio](https://github.com/cococov/Busca-Minas)<br/>
[Flood fill algorithm](https://en.wikipedia.org/wiki/Flood_fill)

### Technologies used

---

+ Languages:
  - Java
+ Frameworks and Libraries:
  - Swing
  - Canvas

### Status

---

Finished. (2017)

### Description

---

My first (programming) personal project.
The game is basicaly a matrix that have a code in every cell:

| código  |    significado   |
| ----------- | ----------------- |
| 0  | no mine and not clicked |
| 1  | one mine nearby  |
| 2  | two mines nearby  |
| 3  | three mines nearby  |
| 4  | four mines nearby  |
| 5  | five mines nearby  |
| 6  | six mines nearby  |
| 7  | seven mines nearby  |
| 8  | eight mines nearby  |
| 9  | mine and not clicked |
| 10 | no mine and clicked |
| 11 | mine and clicked |
| 12 | no mine and flag |
| 13 | mine and flag |
| 14 | mine and lose |

To represent the matrix at the GUI, I use the ``canvas`` of ``java`` and ``java swing`` for the ``UI`` of the game.
For the images I used ``paint``.

## TODO 🚀
- Rewrite the entire game, using my current knowledge and good practices.

![main-minesweeper](https://juanlamas.dev/img/content/minesweeper/main.png "content")
      
![win-minesweeper](https://juanlamas.dev/img/content/minesweeper/win.png "content")
      
![lose-minesweeper](https://juanlamas.dev/img/content/minesweeper/lose.png "content")
