
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;VHUAERE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CVHUAERE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move, keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/FR.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 01:19:39 UTC*,
 - Total moves - 3,
 - Last move has been made - *12/11/2022, 01:22:39 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 46
| Jerry | 38

Now it is Jerry's turn, letters in rack:
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
| 3 | [@radosz99](github.com/radosz99)| 84

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [O:2:evasure](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A2%3Aevasure&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 42 
|2 | [O:0:haveuse](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A0%3Ahaveuse&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 42 
|3 | [O:2:evaser](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A2%3Aevaser&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 39 
|4 | [O:0:havees](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A0%3Ahavees&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 39 
|5 | [O:0:havres](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A0%3Ahavres&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 39 
|6 | [O:0:heveas](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A0%3Aheveas&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 39 
|7 | [O:0:vareuse](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A0%3Avareuse&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 33 
|8 | [O:2:verseau](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A2%3Averseau&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 33 
|9 | [O:0:averes](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A0%3Aaveres&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 30 
|10 | [O:0:heures](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A0%3Aheures&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 30 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|2| INSERT | 5:I:texanes | ['TEXANES'] | 12/11/2022, 01:22:39 UTC | 20 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | K:4:excipa | ['EXCIPA'] | 12/11/2022, 01:21:52 UTC | 38 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:H:kali | ['KALI'] | 12/11/2022, 01:20:40 UTC | 26 | Tom | [@radosz99](github.com/radosz99) |
</details>
    