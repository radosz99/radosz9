
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;DNSARKE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CDNSARKE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/FR.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/11/2022, 19:35:33 UTC*,
 - Number of remaining letters - 40,
 - Total moves - 11,
 - Last move has been made - *12/11/2022, 23:19:58 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 154
| Jerry | 76

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
| 11 | [@radosz99](github.com/radosz99)| 230

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [13:J:kans](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C13%3AJ%3Akans&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 33 
|2 | [J:9:ksar](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CJ%3A9%3Aksar&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 33 
|3 | [3:H:ukase](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C3%3AH%3Aukase&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 28 
|4 | [7:J:dardes](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AJ%3Adardes&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 27 
|5 | [13:L:ksar](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C13%3AL%3Aksar&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 26 
|6 | [1:H:jerkas](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AH%3Ajerkas&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|7 | [7:J:sandre](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AJ%3Asandre&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|8 | [1:H:jerka](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AH%3Ajerka&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 23 
|9 | [1:H:jerks](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AH%3Ajerks&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 23 
|10 | [11:A:ksar](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AA%3Aksar&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 23 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|10| INSERT | M:7:demeles | ['DEMELES'] | 12/11/2022, 23:19:58 UTC | 20 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 10:G:message | ['MESSAGE'] | 12/11/2022, 23:11:18 UTC | 18 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | H:6:aeriez | ['AERIEZ'] | 12/11/2022, 23:10:40 UTC | 25 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | H:1:jeux | ['JEUX'] | 12/11/2022, 23:06:53 UTC | 21 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | 2:C:ehonte | ['EHONTE'] | 12/11/2022, 23:03:18 UTC | 20 | Tom | [@radosz99](github.com/radosz99) |
|5| REPLACE | ['O', 'E', 'E', 'L', 'I', 'N', 'I'] | ['S', 'G', 'U', 'D', 'J', 'M', 'A'] | 12/11/2022, 23:01:13 UTC | 0 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 4:E:voix | ['VOIX'] | 12/11/2022, 22:50:28 UTC | 32 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | F:1:enrolai | ['ENROLAI'] | 12/11/2022, 22:32:48 UTC | 11 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 9:D:dry | ['DRY'] | 12/11/2022, 20:06:46 UTC | 33 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | D:5:tchador | ['TCHADOR'] | 12/11/2022, 19:53:52 UTC | 26 | Jerry | [@radosz99](github.com/radosz99) |
</details>
    