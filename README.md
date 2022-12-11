
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;RISHUAI](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CRISHUAI&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move, keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/FR.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 01:19:39 UTC*,
 - Total moves - 6,
 - Last move has been made - *12/11/2022, 01:26:29 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 72
| Jerry | 114

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
| 6 | [@radosz99](github.com/radosz99)| 186

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [H:9:mirais](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CH%3A9%3Amirais&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|2 | [H:9:murais](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CH%3A9%3Amurais&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|3 | [H:7:kamis](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CH%3A7%3Akamis&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|4 | [H:7:kami](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CH%3A7%3Akami&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|5 | [J:1:hi](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CJ%3A1%3Ahi&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 13 
|6 | [L:1:hou](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CL%3A1%3Ahou&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 12 
|7 | [8:K:phare](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C8%3AK%3Aphare&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|8 | [8:K:phase](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C8%3AK%3Aphase&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|9 | [M:0:rufians](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CM%3A0%3Arufians&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 11 
|10 | [I:9:ahuris](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CI%3A9%3Aahuris&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 10 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|5| INSERT | 9:H:maya | ['MAYA'] | 12/11/2022, 01:26:28 UTC | 34 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 2:I:girofle | ['GIROFLE'] | 12/11/2022, 01:24:51 UTC | 26 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | O:2:evasure | ['EVASURE'] | 12/11/2022, 01:23:57 UTC | 42 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 5:I:texanes | ['TEXANES'] | 12/11/2022, 01:22:39 UTC | 20 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | K:4:excipa | ['EXCIPA'] | 12/11/2022, 01:21:52 UTC | 38 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:H:kali | ['KALI'] | 12/11/2022, 01:20:40 UTC | 26 | Tom | [@radosz99](github.com/radosz99) |
</details>
    