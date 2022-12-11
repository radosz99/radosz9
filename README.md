
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;WVXITOH](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CWVXITOH&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/FR.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 19:35:33 UTC*,
 - Number of remaining letters - 67,
 - Total moves - 4,
 - Last move has been made - *12/11/2022, 22:32:48 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 57
| Jerry | 37

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
| 4 | [@radosz99](github.com/radosz99)| 94

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [4:E:voix](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C4%3AE%3Avoix&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 32 
|2 | [2:F:noix](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AF%3Anoix&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|3 | [3:C:hoir](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C3%3AC%3Ahoir&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|4 | [2:E:inox](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AE%3Ainox&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|5 | [2:C:ovin](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AC%3Aovin&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|6 | [2:C:thon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C2%3AC%3Athon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|7 | [5:B:vit](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C5%3AB%3Avit&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|8 | [3:C:voir](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C3%3AC%3Avoir&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|9 | [4:E:voit](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C4%3AE%3Avoit&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 14 
|10 | [1:F:exit](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AF%3Aexit&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 13 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|3| INSERT | F:1:enrolai | ['ENROLAI'] | 12/11/2022, 22:32:48 UTC | 11 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 9:D:dry | ['DRY'] | 12/11/2022, 20:06:46 UTC | 33 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | D:5:tchador | ['TCHADOR'] | 12/11/2022, 19:53:52 UTC | 26 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:D:haine | ['HAINE'] | 12/11/2022, 19:50:57 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
</details>
    