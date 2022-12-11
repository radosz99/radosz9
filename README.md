
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;WTOHEER](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CWTOHEER&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/FR.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 19:35:33 UTC*,
 - Number of remaining letters - 64,
 - Total moves - 6,
 - Last move has been made - *12/11/2022, 23:01:13 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 89
| Jerry | 37

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
| 6 | [@radosz99](github.com/radosz99)| 126

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [2:C:ehonte](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AC%3Aehonte&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 20 
|2 | [2:B:threne](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AB%3Athrene&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 20 
|3 | [1:A:ethere](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AA%3Aethere&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|4 | [2:B:heron](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AB%3Aheron&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|5 | [1:B:hetre](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AB%3Ahetre&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|6 | [2:C:thon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AC%3Athon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|7 | [2:B:troene](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AB%3Atroene&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|8 | [H:3:ex](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CH%3A3%3Aex&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|9 | [11:A:hetre](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AA%3Ahetre&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|10 | [2:C:reent](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AC%3Areent&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|5| REPLACE | ['O', 'E', 'E', 'L', 'I', 'N', 'I'] | ['S', 'G', 'U', 'D', 'J', 'M', 'A'] | 12/11/2022, 23:01:13 UTC | 0 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 4:E:voix | ['VOIX'] | 12/11/2022, 22:50:28 UTC | 32 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | F:1:enrolai | ['ENROLAI'] | 12/11/2022, 22:32:48 UTC | 11 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 9:D:dry | ['DRY'] | 12/11/2022, 20:06:46 UTC | 33 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | D:5:tchador | ['TCHADOR'] | 12/11/2022, 19:53:52 UTC | 26 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:D:haine | ['HAINE'] | 12/11/2022, 19:50:57 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
</details>
    