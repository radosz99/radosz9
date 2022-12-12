
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;EUNASTE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CEUNASTE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/DE.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/12/2022, 11:56:11 UTC*,
 - Number of remaining letters - 86,
 - Total moves - 0,
    
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
|1 | [7:H:entase](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AH%3Aentase&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|2 | [7:G:entase](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AG%3Aentase&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|3 | [7:D:entase](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AD%3Aentase&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|4 | [7:C:entase](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AC%3Aentase&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|5 | [7:H:neuest](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AH%3Aneuest&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|6 | [7:G:neuest](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AG%3Aneuest&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|7 | [7:D:neuest](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AD%3Aneuest&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|8 | [7:C:neuest](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AC%3Aneuest&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|9 | [7:H:neuste](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AH%3Aneuste&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|10 | [7:G:neuste](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AG%3Aneuste&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
</details>
    