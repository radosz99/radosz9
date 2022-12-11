
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;NIRQEDI](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CNIRQEDI&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 11:52:56 UTC*,
 - Number of remaining letters - 49,
 - Total moves - 8,
 - Last move has been made - *12/11/2022, 14:06:39 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 60
| Jerry | 178

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
| 8 | [@radosz99](github.com/radosz99)| 238

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [12:C:indique](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C12%3AC%3Aindique&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 36 
|2 | [11:F:definir](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AF%3Adefinir&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|3 | [11:F:inferid](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AF%3Ainferid&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|4 | [K:8:cernid](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CK%3A8%3Acernid&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|5 | [11:H:fendi](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AH%3Afendi&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|6 | [11:H:finde](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AH%3Afinde&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|7 | [11:H:finid](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AH%3Afinid&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|8 | [11:H:finire](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AH%3Afinire&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|9 | [11:H:freid](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AH%3Afreid&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|10 | [12:G:quinde](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C12%3AG%3Aquinde&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 17 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|7| INSERT | H:9:difuso | ['DIFUSO'] | 12/11/2022, 14:06:39 UTC | 42 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | 8:I:chucen | ['CHUCEN'] | 12/11/2022, 13:57:36 UTC | 12 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | 1:I:cigarro | ['CIGARRO'] | 12/11/2022, 13:53:41 UTC | 36 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 9:F:yudo | ['YUDO'] | 12/11/2022, 13:50:31 UTC | 16 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | L:1:adensase | ['ADENSASE'] | 12/11/2022, 13:44:00 UTC | 70 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 4:H:lamin | ['LAMIN'] | 12/11/2022, 13:40:50 UTC | 14 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | I:3:zarcecho | ['ZARCECHO'] | 12/11/2022, 13:36:05 UTC | 30 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:H:je | ['JE'] | 12/11/2022, 12:21:25 UTC | 18 | Tom | [@radosz99](github.com/radosz99) |
</details>
    