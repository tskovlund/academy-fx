# Academy FX
Sound effects for the [new front-end implementation](https://github.com/beeracademy/beta-game) of the [Academy](https://academy.beer) game.

Browse and listen to currently available effects at <https://tskovlund.github.io/academy-fx>.

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
| Lobby music | `lobby` | | | | ✅ | |
| Login success | `login_success` | ✅ | | | | |
| Login error | `login_error` | ✅ | | | | |
| Shuffling of players at login | `shuffle` | ✅ | | | ✅ | |
| Shuffle done | `shuffle_done` | Not supported (part of `shuffle`). | | | ✅ | |
| Game starts | `game_start` | ✅ | | | ✅ | |
| Game finishes | `game_finish` | ✅ | | | ✅ | |
| A card is drawn | `draw_card` | ✅ | | | | |
| Value of card drawn | `draw_<value>` | | | | ✅ `ace` | |
| Double kill | `kill_double` | | | | ✅ | |
| Mega kill | `kill_mega` | | | | ✅ | |
| Monster kill | `kill_monster` | | | | ✅ | |
| Multi kill | `kill_multi` | | | | ✅ | |
| Ultra kill | `kill_ultra` | | | | ✅ | |
| All aces have been drawn | `all_aces` | | | | | |
| Extra chug | `chug_extra` | | | | ✅ | |
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
