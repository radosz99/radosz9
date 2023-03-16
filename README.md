
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;URUDETE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CURUDETE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *02/07/2023, 17:49:20 UTC*,
 - Number of remaining letters: 28,
 - Total moves: 11,
 - Last move has been made - *03/16/2023, 11:52:04 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 250
| Jerry | 248

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
| 10 | [@radosz99](github.com/radosz99)| 482
| 1 | [@pieetrus](github.com/pieetrus)| 16

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [O:0:tedero](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A0%3Atedero&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|2 | [O:0:teredo](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A0%3Ateredo&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|3 | [O:4:rodete](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A4%3Arodete&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|4 | [7:L:yure](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AL%3Ayure&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|5 | [7:L:yute](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AL%3Ayute&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|6 | [O:4:rodee](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A4%3Arodee&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|7 | [O:4:dore](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A4%3Adore&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|8 | [O:4:dote](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A4%3Adote&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|9 | [N:5:lleude](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CN%3A5%3Alleude&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
|10 | [O:5:odre](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A5%3Aodre&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 15 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|10| INSERT | 5:L:mello | ['MELLO'] | 03/16/2023, 11:52:04 UTC | 29 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 5:F:morral | ['MORRAL'] | 03/16/2023, 11:44:01 UTC | 22 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | I:2:cegaseis | ['CEGASEIS'] | 03/09/2023, 21:17:53 UTC | 16 | Tom | [@pieetrus](github.com/pieetrus) |
|7| INSERT | 9:B:heredo | ['HEREDO'] | 03/01/2023, 11:44:01 UTC | 22 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | L:3:zumayas | ['ZUMAYAS'] | 03/01/2023, 11:27:21 UTC | 25 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | 3:G:ajenuz | ['AJENUZ'] | 03/01/2023, 11:17:31 UTC | 60 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | G:3:alolaron | ['ALOLARON'] | 02/23/2023, 20:08:34 UTC | 60 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | 13:B:index | ['INDEX'] | 02/23/2023, 20:06:36 UTC | 58 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 11:A:ñorbo | ['ÑORBO'] | 02/11/2023, 12:06:37 UTC | 44 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | C:6:capearon | ['CAPEARON'] | 02/11/2023, 11:49:00 UTC | 86 | Jerry | [@radosz99](github.com/radosz99) |
</details>
    