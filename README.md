
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;QDDSUIO](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CQDDSUIO&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move, keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 01:32:31 UTC*,
 - Total moves - 14,
 - Last move has been made - *12/11/2022, 02:02:21 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 236
| Jerry | 254

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
| 14 | [@radosz99](github.com/radosz99)| 490

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [0:L:bodi](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Abodi&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|2 | [0:L:biso](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Abiso&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|3 | [0:L:bous](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Abous&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|4 | [0:L:buso](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AL%3Abuso&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|5 | [8:C:quios](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C8%3AC%3Aquios&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|6 | [O:3:quisa](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A3%3Aquisa&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|7 | [14:D:quiso](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C14%3AD%3Aquiso&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|8 | [F:1:musido](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A1%3Amusido&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 13 
|9 | [8:C:quio](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C8%3AC%3Aquio&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 13 
|10 | [F:1:muidos](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A1%3Amuidos&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|13| INSERT | O:10:vanos | ['VANOS'] | 12/11/2022, 02:02:21 UTC | 27 | Jerry | [@radosz99](github.com/radosz99) |
|12| INSERT | H:0:uy | ['UY'] | 12/11/2022, 02:01:18 UTC | 15 | Tom | [@radosz99](github.com/radosz99) |
|11| INSERT | 1:F:muyendo | ['MUYENDO'] | 12/11/2022, 02:00:02 UTC | 21 | Jerry | [@radosz99](github.com/radosz99) |
|10| INSERT | F:8:onix | ['ONIX'] | 12/11/2022, 01:57:28 UTC | 13 | Tom | [@radosz99](github.com/radosz99) |
|9| REPLACE | ['T', 'E', 'N', 'L', 'T', 'D', 'E'] | DYENUMR | 12/11/2022, 01:49:30 UTC | 0 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | L:0:bogan | ['BOGAN'] | 12/11/2022, 01:47:36 UTC | 22 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | 7:L:pega | ['PEGA'] | 12/11/2022, 01:46:33 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | M:6:helearia | ['HELEARIA'] | 12/11/2022, 01:45:31 UTC | 82 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | 13:H:escosado | ['ESCOSADO'] | 12/11/2022, 01:42:18 UTC | 84 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 4:H:zorruna | ['ZORRUNA'] | 12/11/2022, 01:40:51 UTC | 44 | Tom | [@radosz99](github.com/radosz99) |
</details>
    