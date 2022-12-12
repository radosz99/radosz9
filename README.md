
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;IAEGISS](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CIAEGISS&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/DE.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/12/2022, 11:56:11 UTC*,
 - Number of remaining letters - 31,
 - Total moves - 11,
 - Last move has been made - *12/12/2022, 13:20:09 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 201
| Jerry | 240

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
| 11 | [@radosz99](github.com/radosz99)| 441

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [5:D:assige](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AD%3Aassige&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 9 
|2 | [5:D:eisige](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AD%3Aeisige&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 9 
|3 | [5:D:essige](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AD%3Aessige&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 9 
|4 | [5:F:gase](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AF%3Agase&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 9 
|5 | [5:F:geie](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AF%3Ageie&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 9 
|6 | [0:J:assige](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AJ%3Aassige&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 8 
|7 | [0:J:eisige](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AJ%3Aeisige&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 8 
|8 | [0:J:essige](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AJ%3Aessige&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 8 
|9 | [5:E:gasse](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AE%3Agasse&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 8 
|10 | [5:E:gisse](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AE%3Agisse&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 8 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|10| INSERT | I:5:einzug | ['EINZUG'] | 12/12/2022, 13:20:09 UTC | 13 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 14:F:rohöle | ['ROHÖLE'] | 12/12/2022, 13:15:04 UTC | 16 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | 9:H:juckt | ['JUCKT'] | 12/12/2022, 13:13:57 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | O:0:eintoren | ['EINTOREN'] | 12/12/2022, 13:13:01 UTC | 131 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | K:2:welk | ['WELK'] | 12/12/2022, 12:59:46 UTC | 20 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | H:11:mich | ['MICH'] | 12/12/2022, 12:58:55 UTC | 39 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 12:F:privaten | ['PRIVATEN'] | 12/12/2022, 12:53:33 UTC | 96 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | 3:J:genäht | ['GENÄHT'] | 12/12/2022, 12:31:18 UTC | 28 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | M:2:fäusten | ['FÄUSTEN'] | 12/12/2022, 12:30:36 UTC | 34 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | K:7:abkamt | ['ABKAMT'] | 12/12/2022, 12:00:45 UTC | 26 | Jerry | [@radosz99](github.com/radosz99) |
</details>
    