
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;YNNIURD](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CYNNIURD&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 11:52:56 UTC*,
 - Number of remaining letters - 65,
 - Total moves - 4,
 - Last move has been made - *12/11/2022, 13:44:00 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 32
| Jerry | 100

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
| 4 | [@radosz99](github.com/radosz99)| 132

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [9:F:yudo](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C9%3AF%3Ayudo&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|2 | [9:H:doy](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C9%3AH%3Adoy&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|3 | [9:F:yiro](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C9%3AF%3Ayiro&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|4 | [1:J:yuan](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AJ%3Ayuan&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|5 | [2:J:urdid](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AJ%3Aurdid&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|6 | [1:J:diay](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AJ%3Adiay&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|7 | [1:K:nadir](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AK%3Anadir&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|8 | [7:L:suni](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AL%3Asuni&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|9 | [7:L:suri](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AL%3Asuri&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|10 | [8:K:dey](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C8%3AK%3Adey&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|3| INSERT | L:1:adensase | ['ADENSASE'] | 12/11/2022, 13:44:00 UTC | 70 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 4:H:lamin | ['LAMIN'] | 12/11/2022, 13:40:50 UTC | 14 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | I:3:zarcecho | ['ZARCECHO'] | 12/11/2022, 13:36:05 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:H:je | ['JE'] | 12/11/2022, 12:21:25 UTC | 18 | Tom | [@radosz99](github.com/radosz99) |
</details>
    