
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;IALÖORE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CIALÖORE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/DE.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/12/2022, 11:56:11 UTC*,
 - Number of remaining letters - 40,
 - Total moves - 9,
 - Last move has been made - *12/12/2022, 13:13:57 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 188
| Jerry | 224

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
| 9 | [@radosz99](github.com/radosz99)| 412

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [F:9:loipe](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A9%3Aloipe&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|2 | [14:F:rohöle](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C14%3AF%3Arohöle&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|3 | [14:F:rohöl](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C14%3AF%3Arohöl&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|4 | [M:10:einöl](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CM%3A10%3Aeinöl&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 13 
|5 | [I:4:ölen](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CI%3A4%3Aölen&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 13 
|6 | [14:H:höre](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C14%3AH%3Ahöre&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|7 | [5:I:lok](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AI%3Alok&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|8 | [14:G:öhre](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C14%3AG%3Aöhre&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|9 | [F:12:pol](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A12%3Apol&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|10 | [5:I:alk](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AI%3Aalk&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|8| INSERT | 9:H:juckt | ['JUCKT'] | 12/12/2022, 13:13:57 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | O:0:eintoren | ['EINTOREN'] | 12/12/2022, 13:13:01 UTC | 131 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | K:2:welk | ['WELK'] | 12/12/2022, 12:59:46 UTC | 20 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | H:11:mich | ['MICH'] | 12/12/2022, 12:58:55 UTC | 39 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 12:F:privaten | ['PRIVATEN'] | 12/12/2022, 12:53:33 UTC | 96 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | 3:J:genäht | ['GENÄHT'] | 12/12/2022, 12:31:18 UTC | 28 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | M:2:fäusten | ['FÄUSTEN'] | 12/12/2022, 12:30:36 UTC | 34 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | K:7:abkamt | ['ABKAMT'] | 12/12/2022, 12:00:45 UTC | 26 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:H:entase | ['ENTASE'] | 12/12/2022, 11:59:14 UTC | 14 | Tom | [@radosz99](github.com/radosz99) |
</details>
    