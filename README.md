
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;YMNLNIN](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CYMNLNIN&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 11:52:56 UTC*,
 - Number of remaining letters - 76,
 - Total moves - 2,
 - Last move has been made - *12/11/2022, 13:36:05 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 18
| Jerry | 30

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
| 2 | [@radosz99](github.com/radosz99)| 48

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [3:G:miz](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C3%3AG%3Amiz&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|2 | [4:H:lamin](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C4%3AH%3Alamin&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|3 | [4:I:alim](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C4%3AI%3Aalim&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|4 | [4:I:amin](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C4%3AI%3Aamin&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|5 | [4:H:lami](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C4%3AH%3Alami&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|6 | [4:H:mali](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C4%3AH%3Amali&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|7 | [4:H:mani](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C4%3AH%3Amani&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|8 | [9:F:mino](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C9%3AF%3Amino&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|9 | [9:F:limon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C9%3AF%3Alimon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|10 | [4:I:ami](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C4%3AI%3Aami&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 10 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|1| INSERT | I:3:zarcecho | ['ZARCECHO'] | 12/11/2022, 13:36:05 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:H:je | ['JE'] | 12/11/2022, 12:21:25 UTC | 18 | Tom | [@radosz99](github.com/radosz99) |
</details>
    