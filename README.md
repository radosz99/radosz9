
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;EIDSBEH](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CEIDSBEH&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/DE.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/12/2022, 11:56:11 UTC*,
 - Number of remaining letters - 22,
 - Total moves - 13,
 - Last move has been made - *12/12/2022, 17:22:30 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 225
| Jerry | 249

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
| 13 | [@radosz99](github.com/radosz99)| 474

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [3:A:behex](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C3%3AA%3Abehex&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 36 
|2 | [H:0:besieg](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CH%3A0%3Abesieg&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 30 
|3 | [1:A:behinds](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AA%3Abehinds&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|4 | [3:C:hexe](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C3%3AC%3Ahexe&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|5 | [D:5:abseihe](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CD%3A5%3Aabseihe&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|6 | [1:A:behind](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AA%3Abehind&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|7 | [3:D:exis](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C3%3AD%3Aexis&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|8 | [1:A:hebend](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AA%3Ahebend&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|9 | [1:A:hebens](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AA%3Ahebens&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|10 | [3:C:hex](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C3%3AC%3Ahex&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|12| INSERT | E:1:nexus | ['NEXUS'] | 12/12/2022, 17:22:29 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|11| INSERT | 5:D:assige | ['ASSIGE'] | 12/12/2022, 14:44:56 UTC | 9 | Jerry | [@radosz99](github.com/radosz99) |
|10| INSERT | I:5:einzug | ['EINZUG'] | 12/12/2022, 13:20:09 UTC | 13 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 14:F:rohöle | ['ROHÖLE'] | 12/12/2022, 13:15:04 UTC | 16 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | 9:H:juckt | ['JUCKT'] | 12/12/2022, 13:13:57 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | O:0:eintoren | ['EINTOREN'] | 12/12/2022, 13:13:01 UTC | 131 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | K:2:welk | ['WELK'] | 12/12/2022, 12:59:46 UTC | 20 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | H:11:mich | ['MICH'] | 12/12/2022, 12:58:55 UTC | 39 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 12:F:privaten | ['PRIVATEN'] | 12/12/2022, 12:53:33 UTC | 96 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | 3:J:genäht | ['GENÄHT'] | 12/12/2022, 12:31:18 UTC | 28 | Jerry | [@radosz99](github.com/radosz99) |
</details>
    