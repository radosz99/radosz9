
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;AACEDOL](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CAACEDOL&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *02/07/2023, 17:49:20 UTC*,
 - Number of remaining letters: 84,
 - Total moves: 0,
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 0
| Jerry | 0

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

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [7:C:acodale](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AC%3Aacodale&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 76 
|2 | [7:D:coleada](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AD%3Acoleada&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 76 
|3 | [7:B:laceado](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AB%3Alaceado&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 76 
|4 | [7:C:ocelada](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AC%3Aocelada&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 76 
|5 | [7:G:coleada](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AG%3Acoleada&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 74 
|6 | [7:G:laceado](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AG%3Alaceado&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 74 
|7 | [7:G:ocelada](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AG%3Aocelada&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 74 
|8 | [7:H:acodale](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AH%3Aacodale&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 72 
|9 | [7:G:acodale](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AG%3Aacodale&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 72 
|10 | [7:F:acodale](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AF%3Aacodale&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 72 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
</details>
    