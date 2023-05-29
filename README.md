
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;UUNTBAE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CUUNTBAE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *02/07/2023, 17:49:20 UTC*,
 - Number of remaining letters: 20,
 - Total moves: 13,
 - Last move has been made - *05/29/2023, 21:08:34 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 271
| Jerry | 272

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
| 12 | [@radosz99](github.com/radosz99)| 527
| 1 | [@pieetrus](github.com/pieetrus)| 16

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [1:J:abuene](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AJ%3Aabuene&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 20 
|2 | [1:J:entube](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AJ%3Aentube&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 20 
|3 | [1:J:atenue](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AJ%3Aatenue&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|4 | [1:K:abete](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AK%3Aabete&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|5 | [1:K:batee](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AK%3Abatee&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|6 | [9:I:subsane](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C9%3AI%3Asubsane&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 13 
|7 | [1:L:bate](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AL%3Abate&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|8 | [1:L:bute](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AL%3Abute&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|9 | [1:L:nube](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AL%3Anube&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|10 | [N:7:nube](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CN%3A7%3Anube&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|12| INSERT | 7:L:yina | ['YINA'] | 05/29/2023, 21:08:24 UTC | 21 | Tom | [@radosz99](github.com/radosz99) |
|11| INSERT | O:0:teredo | ['TEREDO'] | 04/28/2023, 19:29:24 UTC | 24 | Jerry | [@radosz99](github.com/radosz99) |
|10| INSERT | 5:L:mello | ['MELLO'] | 03/16/2023, 11:52:04 UTC | 29 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 5:F:morral | ['MORRAL'] | 03/16/2023, 11:44:01 UTC | 22 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | I:2:cegaseis | ['CEGASEIS'] | 03/09/2023, 21:17:53 UTC | 16 | Tom | [@pieetrus](github.com/pieetrus) |
|7| INSERT | 9:B:heredo | ['HEREDO'] | 03/01/2023, 11:44:01 UTC | 22 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | L:3:zumayas | ['ZUMAYAS'] | 03/01/2023, 11:27:21 UTC | 25 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | 3:G:ajenuz | ['AJENUZ'] | 03/01/2023, 11:17:31 UTC | 60 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | G:3:alolaron | ['ALOLARON'] | 02/23/2023, 20:08:34 UTC | 60 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | 13:B:index | ['INDEX'] | 02/23/2023, 20:06:36 UTC | 58 | Jerry | [@radosz99](github.com/radosz99) |
</details>
    