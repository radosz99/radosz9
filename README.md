
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;QDSNEUD](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CQDSNEUD&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move, keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 01:32:31 UTC*,
 - Total moves - 18,
 - Last move has been made - *12/11/2022, 02:07:21 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 283
| Jerry | 288

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
| 18 | [@radosz99](github.com/radosz99)| 571

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [0:A:dudan](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Adudan&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|2 | [0:A:dudas](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Adudas&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|3 | [0:A:sedad](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Asedad&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|4 | [0:A:sudad](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Asudad&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 21 
|5 | [0:A:duda](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Aduda&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|6 | [0:A:dunas](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Adunas&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|7 | [0:A:nudas](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Anudas&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|8 | [0:A:sedan](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Asedan&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|9 | [0:A:sudan](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C0%3AA%3Asudan&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|10 | [O:3:quedad](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CO%3A3%3Aquedad&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 17 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|17| INSERT | D:0:abuelo | ['ABUELO'] | 12/11/2022, 02:07:21 UTC | 18 | Jerry | [@radosz99](github.com/radosz99) |
|16| INSERT | 2:C:jume | ['JUME'] | 12/11/2022, 02:06:35 UTC | 26 | Tom | [@radosz99](github.com/radosz99) |
|15| INSERT | F:1:mereci | ['MERECI'] | 12/11/2022, 02:05:21 UTC | 16 | Jerry | [@radosz99](github.com/radosz99) |
|14| INSERT | 0:L:bodi | ['BODI'] | 12/11/2022, 02:03:56 UTC | 21 | Tom | [@radosz99](github.com/radosz99) |
|13| INSERT | O:10:vanos | ['VANOS'] | 12/11/2022, 02:02:21 UTC | 27 | Jerry | [@radosz99](github.com/radosz99) |
|12| INSERT | H:0:uy | ['UY'] | 12/11/2022, 02:01:18 UTC | 15 | Tom | [@radosz99](github.com/radosz99) |
|11| INSERT | 1:F:muyendo | ['MUYENDO'] | 12/11/2022, 02:00:02 UTC | 21 | Jerry | [@radosz99](github.com/radosz99) |
|10| INSERT | F:8:onix | ['ONIX'] | 12/11/2022, 01:57:28 UTC | 13 | Tom | [@radosz99](github.com/radosz99) |
|9| REPLACE | ['T', 'E', 'N', 'L', 'T', 'D', 'E'] | DYENUMR | 12/11/2022, 01:49:30 UTC | 0 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | L:0:bogan | ['BOGAN'] | 12/11/2022, 01:47:36 UTC | 22 | Tom | [@radosz99](github.com/radosz99) |
</details>
    