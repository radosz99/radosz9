
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;RANEOPC](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CRANEOPC&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *02/07/2023, 17:49:20 UTC*,
 - Number of remaining letters: 77,
 - Total moves: 1,
 - Last move has been made - *02/07/2023, 17:54:25 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 76
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
| 1 | [@radosz99](github.com/radosz99)| 76

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [C:6:capearon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A6%3Acapearon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 86 
|2 | [C:6:caponare](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A6%3Acaponare&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 86 
|3 | [C:6:caponera](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A6%3Acaponera&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 86 
|4 | [C:5:opacaren](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A5%3Aopacaren&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 86 
|5 | [C:7:aceparon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A7%3Aaceparon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 80 
|6 | [C:7:acoparen](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A7%3Aacoparen&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 80 
|7 | [C:7:apocaren](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A7%3Aapocaren&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 80 
|8 | [C:2:caponare](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A2%3Acaponare&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 78 
|9 | [C:1:copearan](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A1%3Acopearan&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 78 
|10 | [C:0:caponera](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CC%3A0%3Acaponera&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 76 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|0| INSERT | 7:C:acodale | ['ACODALE'] | 02/07/2023, 17:54:25 UTC | 76 | Tom | [@radosz99](github.com/radosz99) |
</details>
    