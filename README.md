
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;DYENUMR](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CDYENUMR&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move, keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 01:32:31 UTC*,
 - Total moves - 11,
 - Last move has been made - *12/11/2022, 01:57:29 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 221
| Jerry | 206

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
| 11 | [@radosz99](github.com/radosz99)| 427

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [O:10:meyor](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A10%3Ameyor&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 33 
|2 | [0:L:buey](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Abuey&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 27 
|3 | [O:11:meon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A11%3Ameon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 27 
|4 | [O:11:muon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A11%3Amuon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 27 
|5 | [O:10:menor](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A10%3Amenor&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|6 | [O:12:doy](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A12%3Adoy&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|7 | [O:11:dron](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A11%3Adron&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|8 | [1:F:muyendo](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AF%3Amuyendo&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|9 | [O:12:yod](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A12%3Ayod&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|10 | [0:L:bren](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Abren&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|10| INSERT | F:8:onix | ['ONIX'] | 12/11/2022, 01:57:28 UTC | 13 | Tom | [@radosz99](github.com/radosz99) |
|9| REPLACE | ['T', 'E', 'N', 'L', 'T', 'D', 'E'] | DYENUMR | 12/11/2022, 01:49:30 UTC | 0 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | L:0:bogan | ['BOGAN'] | 12/11/2022, 01:47:36 UTC | 22 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | 7:L:pega | ['PEGA'] | 12/11/2022, 01:46:33 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | M:6:helearia | ['HELEARIA'] | 12/11/2022, 01:45:31 UTC | 82 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | 13:H:escosado | ['ESCOSADO'] | 12/11/2022, 01:42:18 UTC | 84 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 4:H:zorruna | ['ZORRUNA'] | 12/11/2022, 01:40:51 UTC | 44 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | H:10:aireo | ['AIREO'] | 12/11/2022, 01:39:32 UTC | 18 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 10:E:hipases | ['HIPASES'] | 12/11/2022, 01:38:55 UTC | 48 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | I:3:toalleros | ['TOALLEROS'] | 12/11/2022, 01:37:52 UTC | 74 | Jerry | [@radosz99](github.com/radosz99) |
</details>
    