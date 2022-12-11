
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;RPNBAOA](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CRPNBAOA&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 11:52:56 UTC*,
 - Number of remaining letters - 33,
 - Total moves - 11,
 - Last move has been made - *12/11/2022, 15:33:23 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 182
| Jerry | 205

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
| 11 | [@radosz99](github.com/radosz99)| 387

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [D:7:probana](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CD%3A7%3Aprobana&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 28 
|2 | [K:8:copaban](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acopaban&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
|3 | [K:8:copaba](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acopaba&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|4 | [K:8:cabrona](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acabrona&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|5 | [K:8:caparon](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acaparon&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|6 | [K:8:caponar](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acaponar&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|7 | [K:8:carbona](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acarbona&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|8 | [K:8:coparan](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acoparan&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|9 | [K:8:coraban](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acoraban&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|10 | [K:8:croaban](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acroaban&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|10| INSERT | O:3:trovaren | ['TROVAREN'] | 12/11/2022, 15:33:23 UTC | 86 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 5:L:saxo | ['SAXO'] | 12/11/2022, 15:31:15 UTC | 27 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | 12:C:indique | ['INDIQUE'] | 12/11/2022, 14:18:31 UTC | 36 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | H:9:difuso | ['DIFUSO'] | 12/11/2022, 14:06:39 UTC | 42 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | 8:I:chucen | ['CHUCEN'] | 12/11/2022, 13:57:36 UTC | 12 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | 1:I:cigarro | ['CIGARRO'] | 12/11/2022, 13:53:41 UTC | 36 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 9:F:yudo | ['YUDO'] | 12/11/2022, 13:50:31 UTC | 16 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | L:1:adensase | ['ADENSASE'] | 12/11/2022, 13:44:00 UTC | 70 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 4:H:lamin | ['LAMIN'] | 12/11/2022, 13:40:50 UTC | 14 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | I:3:zarcecho | ['ZARCECHO'] | 12/11/2022, 13:36:05 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
</details>
    