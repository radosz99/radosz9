
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;OONRBÑL](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7COONRBÑL&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *02/07/2023, 17:49:20 UTC*,
 - Number of remaining letters: 70,
 - Total moves: 2,
 - Last move has been made - *02/11/2023, 11:49:00 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 76
| Jerry | 86

Now it is **Tom's** turn, letters in rack:
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
| 2 | [@radosz99](github.com/radosz99)| 162

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [11:A:ñorbo](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AA%3Añorbo&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 44 
|2 | [E:6:ñorbo](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A6%3Añorbo&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 28 
|3 | [E:3:ñorbo](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A3%3Añorbo&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 28 
|4 | [10:B:baño](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C10%3AB%3Abaño&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
|5 | [10:C:añoro](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C10%3AC%3Aañoro&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|6 | [G:6:baño](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A6%3Abaño&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|7 | [G:4:bolaño](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A4%3Abolaño&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|8 | [11:A:borlon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AA%3Aborlon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|9 | [10:B:laño](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C10%3AB%3Alaño&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|10 | [10:B:raño](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C10%3AB%3Araño&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|1| INSERT | C:6:capearon | ['CAPEARON'] | 02/11/2023, 11:49:00 UTC | 86 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:C:acodale | ['ACODALE'] | 02/07/2023, 17:54:25 UTC | 76 | Tom | [@radosz99](github.com/radosz99) |
</details>
    