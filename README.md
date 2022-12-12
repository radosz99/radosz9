
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
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;DTUNXEL](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CDTUNXEL&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip`, for example [scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/DE.png),
 - Game is **IN PROGRESS**,
 - Has begun - *12/12/2022, 11:56:11 UTC*,
 - Number of remaining letters - 26,
 - Total moves - 12,
 - Last move has been made - *12/12/2022, 14:44:56 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 201
| Jerry | 249

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
| 12 | [@radosz99](github.com/radosz99)| 450

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [E:1:nexus](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A1%3Anexus&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|2 | [E:1:tuxes](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A1%3Atuxes&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|3 | [E:3:exst](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CE%3A3%3Aexst&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|4 | [G:3:unix](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A3%3Aunix&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 19 
|5 | [D:5:adulten](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CD%3A5%3Aadulten&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|6 | [D:5:autelnd](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CD%3A5%3Aautelnd&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|7 | [G:4:nix](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A4%3Anix&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|8 | [1:N:xi](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C1%3AN%3Axi&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|9 | [G:5:ix](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CG%3A5%3Aix&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 17 
|10 | [D:3:dualen](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7CD%3A3%3Adualen&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|11| INSERT | 5:D:assige | ['ASSIGE'] | 12/12/2022, 14:44:56 UTC | 9 | Jerry | [@radosz99](github.com/radosz99) |
|10| INSERT | I:5:einzug | ['EINZUG'] | 12/12/2022, 13:20:09 UTC | 13 | Tom | [@radosz99](github.com/radosz99) |
|9| INSERT | 14:F:rohöle | ['ROHÖLE'] | 12/12/2022, 13:15:04 UTC | 16 | Jerry | [@radosz99](github.com/radosz99) |
|8| INSERT | 9:H:juckt | ['JUCKT'] | 12/12/2022, 13:13:57 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|7| INSERT | O:0:eintoren | ['EINTOREN'] | 12/12/2022, 13:13:01 UTC | 131 | Jerry | [@radosz99](github.com/radosz99) |
|6| INSERT | K:2:welk | ['WELK'] | 12/12/2022, 12:59:46 UTC | 20 | Tom | [@radosz99](github.com/radosz99) |
|5| INSERT | H:11:mich | ['MICH'] | 12/12/2022, 12:58:55 UTC | 39 | Jerry | [@radosz99](github.com/radosz99) |
|4| INSERT | 12:F:privaten | ['PRIVATEN'] | 12/12/2022, 12:53:33 UTC | 96 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | 3:J:genäht | ['GENÄHT'] | 12/12/2022, 12:31:18 UTC | 28 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | M:2:fäusten | ['FÄUSTEN'] | 12/12/2022, 12:30:36 UTC | 34 | Tom | [@radosz99](github.com/radosz99) |
</details>
    