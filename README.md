
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;IGOCRORR](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CIGOCRORR&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 11:52:56 UTC*,
 - Number of remaining letters - 62,
 - Total moves - 5,
 - Last move has been made - *12/11/2022, 13:50:31 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 48
| Jerry | 100

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
| 5 | [@radosz99](github.com/radosz99)| 148

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [1:I:cigarro](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AI%3Acigarro&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 36 
|2 | [1:H:corria](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AH%3Acorria&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 30 
|3 | [1:H:corroa](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AH%3Acorroa&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 30 
|4 | [H:9:dorico](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CH%3A9%3Adorico&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 30 
|5 | [1:K:carro](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AK%3Acarro&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
|6 | [1:K:garrio](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AK%3Agarrio&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
|7 | [1:K:garrir](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AK%3Agarrir&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
|8 | [1:F:corroiga](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AF%3Acorroiga&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 25 
|9 | [6:I:cigarro](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C6%3AI%3Acigarro&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|10 | [1:K:garri](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AK%3Agarri&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|4| INSERT | 9:F:yudo | ['YUDO'] | 12/11/2022, 13:50:31 UTC | 16 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | L:1:adensase | ['ADENSASE'] | 12/11/2022, 13:44:00 UTC | 70 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 4:H:lamin | ['LAMIN'] | 12/11/2022, 13:40:50 UTC | 14 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | I:3:zarcecho | ['ZARCECHO'] | 12/11/2022, 13:36:05 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:H:je | ['JE'] | 12/11/2022, 12:21:25 UTC | 18 | Tom | [@radosz99](github.com/radosz99) |
</details>
    