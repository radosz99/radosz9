
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;TEQORGR](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CTEQORGR&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/GB.png),
 - Game is **IN PROGRESS**,
 - Has begun - *01/05/2023, 12:08:20 UTC*,
 - Number of remaining letters: 40,
 - Total moves: 11,
 - Last move has been made - *02/07/2023, 14:10:15 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 215
| Jerry | 104

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
| 10 | [@radosz99](github.com/radosz99)| 299
| 1 | [@pieetrus](github.com/pieetrus)| 20

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [7:J:droger](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AJ%3Adroger&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 27 
|2 | [7:J:dorter](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AJ%3Adorter&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|3 | [N:0:forger](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CN%3A0%3Aforger&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|4 | [N:0:forget](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CN%3A0%3Aforget&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|5 | [2:I:qi](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AI%3Aqi&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|6 | [N:0:forge](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CN%3A0%3Aforge&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|7 | [2:I:girner](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AI%3Agirner&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|8 | [N:0:fetor](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CN%3A0%3Afetor&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|9 | [N:0:forte](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CN%3A0%3Aforte&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|10 | [N:0:frog](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CN%3A0%3Afrog&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|10| INSERT | J:2:intruded | ['INTRUDED'] | 02/07/2023, 14:10:15 UTC | 66 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 0:L:jafa | ['JAFA'] | 01/30/2023, 22:17:11 UTC | 42 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | L:0:janty | ['JANTY'] | 01/30/2023, 22:16:22 UTC | 46 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | 4:H:putty | ['PUTTY'] | 01/10/2023, 16:39:07 UTC | 20 | Jerry | [@pieetrus](github.com/pieetrus) |
|6| INSERT | E:10:flam | ['FLAM'] | 01/06/2023, 18:46:43 UTC | 18 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | 12:C:knave | ['KNAVE'] | 01/06/2023, 18:31:03 UTC | 24 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | G:7:excuse | ['EXCUSE'] | 01/06/2023, 18:18:15 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | H:4:pont | ['PONT'] | 01/06/2023, 18:15:05 UTC | 6 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 5:E:dzho | ['DZHO'] | 01/06/2023, 18:05:19 UTC | 37 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | E:4:adios | ['ADIOS'] | 01/05/2023, 13:12:45 UTC | 12 | Jerry | [@radosz99](github.com/radosz99) |
</details>
    