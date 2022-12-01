# Hackathon
Hackathon where participants compete to create the best algorithm for Tetris. Used as the Computing Society's round on 28/10/2022 for the Computer Science department's hackathon with ~100 participants.

Competitors were given the state of the board and the falling piece, and had to return whether to do nothing, drop, rotate, or move the piece.

## Results
Each submission was tested on 100,000 games of Tetris.
| Team name       | Avg     | S.D. | Avg row clears | High score |
|-----------------|---------|------|----------------|------------|
| Overwriters     | 146.2   | 51   | 0.687          | 565        |
| ergjje          | 80.7088 | 16   | 0.00926        | 230        |
| mond.ran()      | 79.0417 | 15   | 0.00786        | 220        |
| castle          | 78.143  | 9    | 0              | 135        |
| The Winners     | 76.7826 | 15   | 0.00487        | 225        |
| Four Musketeers | 75.9298 | 14   | 0.00716        | 200        |
| 50% Blind       | 70.7837 | 12   | 0.00006        | 170        |
| m1mac           | 56.5365 | 10   | 0.00011        | 140        |
| Luca Bedford    | 39.78   | 5    | 0              | 65         |
| STAR            | 39.61   | 4    | 0              | 50         |

## Video
I made a program which converted each team's best game into a video, and combined them to announce the results on YouTube.
[![Tetris Hackathon Results Video](https://img.youtube.com/vi/fiCimSpGldQ/0.jpg)](https://www.youtube.com/watch?v=fiCimSpGldQ)

## Hackathon Instructions
- Extract `tetris.py` and `tetris_ai.py` into a folder.
- Complete the `move_piece` function in the `tetris_ai.py` file.
- Do not modify the `tetris.py` file.
- Run `tetris.py` from console to test.
- Highest average score wins!
