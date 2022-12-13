
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;DFEDORR](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CDFEDORR&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/DE.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/12/2022, 11:56:11 UTC*,
 - Number of remaining letters - 3,
 - Total moves - 18,
 - Last move has been made - *12/13/2022, 15:24:27 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 306
| Jerry | 339

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
| 18 | [@radosz99](github.com/radosz99)| 645

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [11:A:dorfes](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AA%3Adorfes&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|2 | [11:B:dorfs](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AB%3Adorfs&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|3 | [11:B:fords](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AB%3Afords&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|4 | [11:A:orders](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AA%3Aorders&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|5 | [11:A:ordres](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AA%3Aordres&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|6 | [11:A:dorers](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AA%3Adorers&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|7 | [11:A:roders](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AA%3Aroders&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|8 | [1:G:darf](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AG%3Adarf&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|9 | [1:G:fado](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AG%3Afado&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|10 | [11:D:fes](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AD%3Afes&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|17| INSERT | H:0:mausig | ['MAUSIG'] | 12/13/2022, 15:24:27 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
|16| INSERT | 1:A:iqs | ['IQS'] | 12/13/2022, 15:17:30 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|15| INSERT | F:11:spür | ['SPÜR'] | 12/13/2022, 15:14:49 UTC | 24 | Jerry | [@radosz99](github.com/radosz99) |
|14| INSERT | A:0:tilbury | ['TILBURY'] | 12/13/2022, 15:07:26 UTC | 57 | Tom | [@radosz99](github.com/radosz99) |
|13| INSERT | 3:A:behex | ['BEHEX'] | 12/13/2022, 15:06:15 UTC | 36 | Jerry | [@radosz99](github.com/radosz99) |
|12| INSERT | E:1:nexus | ['NEXUS'] | 12/12/2022, 17:22:29 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|11| INSERT | 5:D:assige | ['ASSIGE'] | 12/12/2022, 14:44:56 UTC | 9 | Jerry | [@radosz99](github.com/radosz99) |
|10| INSERT | I:5:einzug | ['EINZUG'] | 12/12/2022, 13:20:09 UTC | 13 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 14:F:rohöle | ['ROHÖLE'] | 12/12/2022, 13:15:04 UTC | 16 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | 9:H:juckt | ['JUCKT'] | 12/12/2022, 13:13:57 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
</details>
    