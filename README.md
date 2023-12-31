# Academy FX
Sound effects for the [new front-end implementation](https://github.com/beeracademy/beta-game) of the [Academy](https://academy.beer) game.

Browse and listen to currently available effects at <https://tskovlund.github.io/academy-fx>.

## Setup
Add pre-commit and post-commit hooks to automatically generate `index.html` and add it to the commit:

```$ ln -s -f ../../pre-commit .git/hooks/pre-commit```

```$ ln -s -f ../../post-commit .git/hooks/post-commit```

## List of effects
The following section gives an overview of effects already produced and to be produced.

The effects are organized in several sound packages/themes to accommodate player preferences.
  - **Digital:** A modern, or even futuristic, theme with lots of reverb.
  - **Analogue:** A theme with samples that resembles the good old days when Academy was played without computers.
  - **Fun:** A fun theme.
  - **Legacy:** Paying homage to the previous version(s) of Academy.
  - **Old:** Commentary by Mathias Old Jensen.


| Effect | Slug | Digital | Analogue | Fun | Legacy | Old |
| ------ | ---- | ------- | -------- | --- | ------ | --- |
| Lobby music | `lobby` | | | | ✅ | ✅ |
| Login success | `login_success` | ✅ | | | | ✅|
| Login error | `login_error` | ✅ | | | | ✅ |
| Shuffling of players at login | `shuffle` | ✅ | | | ✅ | ✅ |
| Shuffle done | `shuffle_done` | Not supported (part of `shuffle`) | | | ✅ | ✅ |
| Game starts | `game_start` | ✅ | | | ✅ | ✅ |
| Game finishes | `game_finish` | ✅ | | | ✅ | ✅ |
| A card is drawn | `draw_card` | Not supported | | | | Not supported |
| Value of card drawn | `draw_[suit_]<value>` | ✅ `two` <br> ✅ `three` <br> ✅ `four` <br> ✅ `five` <br> ✅ `six` <br> ✅ `seven` <br> ✅ `eight` <br> ✅ `nine` <br> ✅ `ten` <br> ✅ `jack` <br> ✅ `queen` <br> ✅ `king` <br> ✅ `ace` | | | ✅ `ace` | ✅ `diamond_two` <br> ✅ `diamond_three` <br> ✅ `diamond_four` <br> ✅ `diamond_five` <br> ✅ `diamond_six` <br> ✅ `diamond_seven` <br> ✅ `diamond_eight` <br> ✅ `diamond_nine` <br> ✅ `diamond_ten` <br> ✅ `diamond_jack` <br> ✅ `diamond_queen` <br> ✅ `diamond_king` <br> ✅ `spade_two` <br> ✅ `spade_three` <br> ✅ `spade_four` <br> ✅ `spade_five` <br> ✅ `spade_six` <br> ✅ `spade_seven` <br> ✅ `spade_eight` <br> ✅ `spade_nine` <br> ✅ `spade_ten` <br> ✅ `spade_jack` <br> ✅ `spade_queen` <br> ✅ `spade_king` <br> ✅ `heart_two` <br> ✅ `heart_three` <br> ✅ `heart_four` <br> ✅ `heart_five` <br> ✅ `heart_six` <br> ✅ `heart_seven` <br> ✅ `heart_eight` <br> ✅ `heart_nine` <br> ✅ `heart_ten` <br> ✅ `heart_jack` <br> ✅ `heart_queen` <br> ✅ `heart_king` <br>  ✅ `club_two` <br> ✅ `club_three` <br> ✅ `club_four` <br> ✅ `club_five` <br> ✅ `club_six` <br> ✅ `club_seven` <br> ✅ `club_eight` <br> ✅ `club_nine` <br> ✅ `club_ten` <br> ✅ `club_jack` <br> ✅ `club_queen` <br> ✅ `club_king` <br> ✅ `ace` <br> |
| Double kill | `kill_double` | ✅ | | | ✅ | ✅ |
| Triple kill | `kill_triple` | ✅ | | | ✅ | ✅ |
| Ultra kill | `kill_ultra` | ✅| | | ✅ | ✅ |
| Mega kill | `kill_mega` | ✅ | | | ✅ | ✅ |
| Monster kill | `kill_monster` | ✅ | | | ✅ | ✅ |
| Multi kill | `kill_multi` | Not supported | | | ✅ | Not supported |
| Extra chug | `chug_extra` | | | | ✅ | |
| All aces have been drawn | `all_aces` | | | | | |
| Chugging music | `chug[_variant]` | | | | ✅ `bubbi_fuve` <br> ✅ `big_chungus` <br> ✅ `mimimi` <br> ✅ `mimimi_spedup` | |
| Insane chug | `chug_insane` | | | | ✅ | |
| Fast chug | `chug_fast` | | | | ✅ | |
| Normal chug | `chug_normal` | | | | ✅ | |
| Slow chug | `chug_slow` | | | | ✅ | |
| Last round begins | `last_round` | | | | | |
| Last round intense music | `last_round_music` | | | | | |
| Change to simple mode (big numbers on card) | `mode_simple` | | | | | |
| Change to advanced mode | `mode_advanced` | | | | | |
| Change to dark theme | `theme_dark` | | | | | |
| Change to light theme | `theme_light` | | | | | |
| Game music/soundscape | `music` | | | | | |
| Player DNF | `dnf_player` | | | | | |
| Game DNF | `dnf_game` | | | | | |
| New player in first position | `crown` | | | | ✅ | |
| New player in last position | `joker` | | | | | |
| Player turn has taken too long ("Den lange tast") | `player_slow` | | | | ✅ | |
| Player time exceeds an hour | `player_hour` | | | | | |
| A round was completed quickly | `round_quick` | | | | | |
| A round was completed slowly | `round_slow` | | | | | |
| Click | `click` | | | | ✅ | |
| Snack | `snack` | | | | ✅ | |
| Loser | `loser` | | | | ✅ | |
| Oops | `oops` | | | | ✅ | |

### Easter eggs
| Effect | Slug | Digital | Analogue | Fun | Legacy | Old |
| ------ | ---- | ------- | -------- | --- | ------ | --- |
| Special anniversary (mod 100) | `anniversary` | | | | | |
| It's not a dick | `dick` | | | | ✅ | |
| Old | `old` | | | | ✅ | |
| Benjamin | `benjamin` | | | | ✅ | |
| Ole Vedel | `ole_vedel` | | | | ✅ | |
