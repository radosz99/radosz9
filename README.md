
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;TEQAOFA](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CTEQAOFA&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/GB.png),
 - Game is **IN PROGRESS**,
 - Has begun - *01/05/2023, 12:08:20 UTC*,
 - Number of remaining letters: 50,
 - Total moves: 9,
 - Last move has been made - *01/30/2023, 22:16:22 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 149
| Jerry | 62

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
| 8 | [@radosz99](github.com/radosz99)| 191
| 1 | [@pieetrus](github.com/pieetrus)| 20

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [0:L:jafa](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Ajafa&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 42 
|2 | [0:L:jato](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Ajato&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 33 
|3 | [0:L:jeat](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Ajeat&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 33 
|4 | [0:L:jota](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Ajota&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 33 
|5 | [2:J:qanat](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AJ%3Aqanat&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 28 
|6 | [2:I:faena](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AI%3Afaena&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|7 | [J:1:fetta](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CJ%3A1%3Afetta&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|8 | [1:J:feat](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AJ%3Afeat&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|9 | [J:1:feat](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CJ%3A1%3Afeat&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|10 | [J:1:fett](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CJ%3A1%3Afett&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|8| INSERT | L:0:janty | ['JANTY'] | 01/30/2023, 22:16:22 UTC | 46 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | 4:H:putty | ['PUTTY'] | 01/10/2023, 16:39:07 UTC | 20 | Jerry | [@pieetrus](github.com/pieetrus) |
|6| INSERT | E:10:flam | ['FLAM'] | 01/06/2023, 18:46:43 UTC | 18 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | 12:C:knave | ['KNAVE'] | 01/06/2023, 18:31:03 UTC | 24 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | G:7:excuse | ['EXCUSE'] | 01/06/2023, 18:18:15 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | H:4:pont | ['PONT'] | 01/06/2023, 18:15:05 UTC | 6 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 5:E:dzho | ['DZHO'] | 01/06/2023, 18:05:19 UTC | 37 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | E:4:adios | ['ADIOS'] | 01/05/2023, 13:12:45 UTC | 12 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:D:volet | ['VOLET'] | 01/05/2023, 12:11:23 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
</details>
    