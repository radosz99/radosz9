
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;IEEIBIE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CIEEIBIE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/25/2022, 22:07:55 UTC*,
 - Number of remaining letters - 61,
 - Total moves - 5,
 - Last move has been made - *12/25/2022, 23:32:19 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 81
| Jerry | 109

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
| 5 | [@radosz99](github.com/radosz99)| 190

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [J:5:bio](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CJ%3A5%3Abio&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|2 | [6:L:cebe](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C6%3AL%3Acebe&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 9 
|3 | [I:7:cea](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CI%3A7%3Acea&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 6 
|4 | [I:7:cia](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CI%3A7%3Acia&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 6 
|5 | [8:L:he](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C8%3AL%3Ahe&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 6 
|6 | [8:L:hi](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C8%3AL%3Ahi&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 6 
|7 | [10:L:tibe](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C10%3AL%3Atibe&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 6 
|8 | [I:9:abe](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CI%3A9%3Aabe&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 5 
|9 | [11:L:abe](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AL%3Aabe&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 5 
|10 | [6:L:ce](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C6%3AL%3Ace&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 5 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|4| INSERT | O:3:mides | ['MIDES'] | 12/25/2022, 23:32:19 UTC | 33 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | 9:I:azoe | ['AZOE'] | 12/25/2022, 23:08:52 UTC | 33 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 4:K:cepti | ['CEPTI'] | 12/25/2022, 22:39:01 UTC | 18 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | L:4:encoheta | ['ENCOHETA'] | 12/25/2022, 22:23:22 UTC | 76 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:H:acojo | ['ACOJO'] | 12/25/2022, 22:08:36 UTC | 30 | Tom | [@radosz99](github.com/radosz99) |
</details>
    