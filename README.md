
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;TEGLLDLA](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CTEGLLDLA&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 11:52:56 UTC*,
 - Number of remaining letters - 0,
 - Total moves - 18,
 - Last move has been made - *12/11/2022, 18:30:38 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 246
| Jerry | 374

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
| 18 | [@radosz99](github.com/radosz99)| 620

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [0:A:lleca](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Alleca&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 42 
|2 | [1:A:alludel](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AA%3Aalludel&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 32 
|3 | [1:B:dulleta](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AB%3Adulleta&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 32 
|4 | [11:J:llegad](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AJ%3Allegad&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 28 
|5 | [0:A:gacel](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Agacel&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 27 
|6 | [F:11:tilla](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A11%3Atilla&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 27 
|7 | [F:11:tille](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A11%3Atille&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 27 
|8 | [12:K:agalle](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C12%3AK%3Aagalle&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
|9 | [12:K:allega](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C12%3AK%3Aallega&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
|10 | [11:J:detall](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AJ%3Adetall&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|17| INSERT | C:0:cumbral | ['CUMBRAL'] | 12/11/2022, 18:30:37 UTC | 28 | Jerry | [@radosz99](github.com/radosz99) |
|16| INSERT | 4:A:perues | ['PERUES'] | 12/11/2022, 18:22:32 UTC | 16 | Tom | [@radosz99](github.com/radosz99) |
|15| INSERT | 14:J:hostie | ['HOSTIE'] | 12/11/2022, 18:17:26 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
|14| INSERT | K:8:coñeado | ['COÑEADO'] | 12/11/2022, 18:03:16 UTC | 34 | Tom | [@radosz99](github.com/radosz99) |
|13| INSERT | A:3:aposenta | ['APOSENTA'] | 12/11/2022, 15:50:25 UTC | 83 | Jerry | [@radosz99](github.com/radosz99) |
|12| INSERT | 10:A:alobe | ['ALOBE'] | 12/11/2022, 15:46:26 UTC | 14 | Tom | [@radosz99](github.com/radosz99) |
|11| INSERT | D:7:probana | ['PROBANA'] | 12/11/2022, 15:36:09 UTC | 28 | Jerry | [@radosz99](github.com/radosz99) |
|10| INSERT | O:3:trovaren | ['TROVAREN'] | 12/11/2022, 15:33:23 UTC | 86 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 5:L:saxo | ['SAXO'] | 12/11/2022, 15:31:15 UTC | 27 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | 12:C:indique | ['INDIQUE'] | 12/11/2022, 14:18:31 UTC | 36 | Tom | [@radosz99](github.com/radosz99) |
</details>
    