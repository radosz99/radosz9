
# GitHub Scrabble Tournament
Play in GitHub Scrabble Tournament and make moves by creating issues according to the rules.    
Inspired by [Tim's Community Chess Tournament](https://github.com/timburgan/).

<details>
  <summary>Start new game</summary>
  
 
 - [GB](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CGB&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/GB.png)
 - [PL](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CPL&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/PL.png)
 - [ES](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CES&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png)
 - [DE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CDE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/DE.png)
 - [FR](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CFR&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/FR.png)
</details>
        

## Rules
 - **inserting letters** - raise an issue with title `scrabble|move|X:Y:WORD`, where `X` and `Y` are coordinates, and `WORD` is string containing player's letter and letters from board, for example [scrabble&#124;move&#124;7:A:BRIDE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AA%3ABRIDE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) if you want to create word `BRIDE` in 7th row starting from column A (RIDE is already on the board) and B is in player's letters. Number should go first if word is horizontal (7:A) or second if word is vertical (A:7). For more details see [notation system](https://en.wikipedia.org/wiki/Scrabble#Notation_system) and examples in [cheater section](#cheater),
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;TTATISD](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CTTATISD&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/GB.png),
 - Game is **IN PROGRESS**,
 - Has begun - *01/05/2023, 12:08:20 UTC*,
 - Number of remaining letters: 79,
 - Total moves: 1,
 - Last move has been made - *01/05/2023, 12:11:23 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 24
| Jerry | 0

Now it is **Jerry's** turn, letters in rack:
<p align="center">
    <img src="https://raw.githubusercontent.com/radosz99/radosz99/main/rack.png" width=30% alt="Img"/>
</p>

Board:
<p align="center">
<img src="https://raw.githubusercontent.com/radosz99/radosz99/main/board.png" width=60% alt="Img"/>
</p>
    
## User leaderboard
| Moves | Who | Points |
| - | - | - |
| 1 | [@radosz99](github.com/radosz99)| 24

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [D:7:vista](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CD%3A7%3Avista&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|2 | [D:7:vitas](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CD%3A7%3Avitas&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|3 | [D:7:vitta](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CD%3A7%3Avitta&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|4 | [E:3:dattos](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A3%3Adattos&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|5 | [E:5:diotas](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A5%3Adiotas&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|6 | [E:3:dittos](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A3%3Adittos&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|7 | [E:4:adios](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A4%3Aadios&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|8 | [E:4:aidos](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A4%3Aaidos&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|9 | [F:5:dalis](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A5%3Adalis&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|10 | [F:5:dalts](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A5%3Adalts&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|0| INSERT | 7:D:volet | ['VOLET'] | 01/05/2023, 12:11:23 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
</details>
    