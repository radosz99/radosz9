
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;TG](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CTG&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **FINISHED, reason: Jerry has got rid of all letters and no more letters are available in letter bag**,
 - Has begun - *12/11/2022, 11:52:56 UTC*,
 - Number of remaining letters - 0,
 - Total moves - 20,
 - Last move has been made - *12/11/2022, 19:34:31 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 275
| Jerry | 392

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
| 20 | [@radosz99](github.com/radosz99)| 667

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [9:N:ge](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C9%3AN%3Age&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 7 
|2 | [G:8:gu](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A8%3Agu&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 5 
|3 | [11:K:et](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AK%3Aet&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 4 
|4 | [9:N:te](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C9%3AN%3Ate&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 4 
|5 | [N:13:ti](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CN%3A13%3Ati&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 4 
|6 | [O:13:ge](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A13%3Age&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 3 
|7 | [11:J:ge](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AJ%3Age&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 3 
|8 | [E:3:ge](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A3%3Age&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 3 
|9 | [E:0:ge](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A0%3Age&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 3 
|10 | [G:8:tu](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A8%3Atu&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 3 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|19| INSERT | A:0:ha | ['HA'] | 12/11/2022, 19:34:31 UTC | 15 | Jerry | [@radosz99](github.com/radosz99) |
|18| INSERT | 1:A:alludel | ['ALLUDEL'] | 12/11/2022, 19:33:28 UTC | 32 | Tom | [@radosz99](github.com/radosz99) |
|17| INSERT | C:0:cumbral | ['CUMBRAL'] | 12/11/2022, 18:30:37 UTC | 28 | Jerry | [@radosz99](github.com/radosz99) |
|16| INSERT | 4:A:perues | ['PERUES'] | 12/11/2022, 18:22:32 UTC | 16 | Tom | [@radosz99](github.com/radosz99) |
|15| INSERT | 14:J:hostie | ['HOSTIE'] | 12/11/2022, 18:17:26 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
|14| INSERT | K:8:coñeado | ['COÑEADO'] | 12/11/2022, 18:03:16 UTC | 34 | Tom | [@radosz99](github.com/radosz99) |
|13| INSERT | A:3:aposenta | ['APOSENTA'] | 12/11/2022, 15:50:25 UTC | 83 | Jerry | [@radosz99](github.com/radosz99) |
|12| INSERT | 10:A:alobe | ['ALOBE'] | 12/11/2022, 15:46:26 UTC | 14 | Tom | [@radosz99](github.com/radosz99) |
|11| INSERT | D:7:probana | ['PROBANA'] | 12/11/2022, 15:36:09 UTC | 28 | Jerry | [@radosz99](github.com/radosz99) |
|10| INSERT | O:3:trovaren | ['TROVAREN'] | 12/11/2022, 15:33:23 UTC | 86 | Tom | [@radosz99](github.com/radosz99) |
</details>
    