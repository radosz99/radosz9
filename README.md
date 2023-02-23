
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;NRLOALO](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CNRLOALO&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *02/07/2023, 17:49:20 UTC*,
 - Number of remaining letters: 62,
 - Total moves: 4,
 - Last move has been made - *02/23/2023, 20:06:46 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 120
| Jerry | 144

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
| 4 | [@radosz99](github.com/radosz99)| 264

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [G:3:alolaron](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A3%3Aalolaron&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 60 
|2 | [I:4:lolearon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CI%3A4%3Alolearon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 60 
|3 | [E:9:alolen](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A9%3Aalolen&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|4 | [E:3:loaron](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A3%3Aloaron&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|5 | [F:5:ladron](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A5%3Aladron&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|6 | [A:9:laño](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CA%3A9%3Alaño&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|7 | [F:4:lardon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A4%3Alardon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|8 | [F:4:loador](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CF%3A4%3Aloador&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|9 | [9:A:olearon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C9%3AA%3Aolearon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|10 | [A:9:raño](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CA%3A9%3Araño&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|3| INSERT | 13:B:index | ['INDEX'] | 02/23/2023, 20:06:36 UTC | 58 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 11:A:ñorbo | ['ÑORBO'] | 02/11/2023, 12:06:37 UTC | 44 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | C:6:capearon | ['CAPEARON'] | 02/11/2023, 11:49:00 UTC | 86 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:C:acodale | ['ACODALE'] | 02/07/2023, 17:54:25 UTC | 76 | Tom | [@radosz99](github.com/radosz99) |
</details>
    