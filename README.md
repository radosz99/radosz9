
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;EMHUOCZ](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CEMHUOCZ&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/GB.png),
 - Game is **IN PROGRESS**,
 - Has begun - *01/05/2023, 12:08:20 UTC*,
 - Number of remaining letters: 75,
 - Total moves: 2,
 - Last move has been made - *01/05/2023, 13:12:45 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 24
| Jerry | 12

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
| 2 | [@radosz99](github.com/radosz99)| 36

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [5:E:dzho](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AE%3Adzho&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 37 
|2 | [5:E:dzo](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AE%3Adzo&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 33 
|3 | [G:5:chez](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A5%3Achez&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 32 
|4 | [G:6:meze](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A6%3Ameze&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 28 
|5 | [H:2:chometz](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CH%3A2%3Achometz&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 27 
|6 | [G:5:mzee](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A5%3Amzee&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
|7 | [G:4:coze](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A4%3Acoze&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 25 
|8 | [G:4:meze](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A4%3Ameze&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 25 
|9 | [G:4:moze](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A4%3Amoze&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 25 
|10 | [G:6:zee](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A6%3Azee&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 23 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|1| INSERT | E:4:adios | ['ADIOS'] | 01/05/2023, 13:12:45 UTC | 12 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:D:volet | ['VOLET'] | 01/05/2023, 12:11:23 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
</details>
    