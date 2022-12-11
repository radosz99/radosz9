
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;ENETSOA](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CENETSOA&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move, keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/FR.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 01:19:39 UTC*,
 - Total moves - 2,
 - Last move has been made - *12/11/2022, 01:21:53 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 26
| Jerry | 38

Now it is Tom's turn, letters in rack:
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
| 2 | [@radosz99](github.com/radosz99)| 64

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [5:I:texanes](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AI%3Atexanes&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 20 
|2 | [5:J:axones](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AJ%3Aaxones&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 19 
|3 | [5:J:extase](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AJ%3Aextase&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 19 
|4 | [5:I:taxees](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AI%3Ataxees&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 19 
|5 | [5:I:taxons](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AI%3Ataxons&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 19 
|6 | [5:I:texane](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AI%3Atexane&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 19 
|7 | [5:I:texans](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AI%3Atexans&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 19 
|8 | [5:J:axees](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AJ%3Aaxees&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|9 | [5:J:axent](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AJ%3Aaxent&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|10 | [5:J:axone](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AJ%3Aaxone&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|1| INSERT | K:4:excipa | ['EXCIPA'] | 12/11/2022, 01:21:52 UTC | 38 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:H:kali | ['KALI'] | 12/11/2022, 01:20:40 UTC | 26 | Tom | [@radosz99](github.com/radosz99) |
</details>
    