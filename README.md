#### Please report any issues here, or in my mod's [thread](https://discord.com/channels/1116389027176787968/1335324781528092672) in the Balatro Discord. Alternatively, report them as a tester in the mod's [official server](https://discord.gg/QwJtrdy4xS). Thank you for playing, and please enjoy...

<p align="center"><img width="568" height="400" alt="hyperfixation logo" src="https://github.com/user-attachments/assets/d03466b2-eb50-414e-bb8a-84dad4a61756" />
<p align="center">a content-ish mod.



## Patches:
### <ins>Inscryption</ins>

__card__
- Ijiraq cardTable assignments
- Ijiraq object assignments
- Astronomer? functionality

__common_events__
- Ijiraq effect merging
- Ijiraq description rendering

__state_events__
- Transformations on dollar bonuses
- Splash? functionality

### <ins>The Binding of Isaac</ins>

__state_events__
- Mary's unlock condition

__blind__
- Blind name storing

### <ins>Miscellaneous</ins>

__state_events__
- custom post-discard context

## Overrides:
### <ins>Inscryption</ins>

__Blind.defeat__
- Special Dagger's debuff tracking

__get_new_boss__
- Pareidolia? functionality

__Card:update__
- custom card-drag detection context

__Card:calculate_joker__
- Jokester flip animation

__generate_card_ui__
- Jokester automatic description generation

__Card:set_cost__
- Astronomer? functionality
- Astronomer-Ijiraq functionality

__Card:add_to_deck__
- Jokester sticker application

__Card:highlight__
- SHED button toggle logic

__Card:can_sell_card__
- Priceless functionality
- Luchador-Ijiraq functionality

__Card:set_ability__
- Boulder functionality

__unlock_card__
- Tetoraq tweaks

__Game:init_game_object__
- Costume functionality

__Game:start_run__
- Card:set_card_rate(card_kind, new_rate)

### <ins>Game:start_run(args)</ins>

__Inscryption__


### <ins>Blind:defeat(silent)</ins>

__The Binding of Isaac__
- Cyanosis' unlock condition

### <ins>Card:calculate_joker(context)</ins>

__Inscryption__
- automatic transformations (disguised)
- automatic animations (disguised)

### <ins>SMODS.pseudorandom_probability(trigger_obj, seed, base_numerator, base_denominator, identifier)</ins>

__The Binding of Isaac__
- Farmer's unlock condition

### <ins>win_game()</ins>

__4Fun__
- Space Needle's unlock condition
- No Bitches?' unlock condition

### <ins>ease_hands_played(mod, instant)</ins>

__Inscryption__
- custom hand change context

### <ins>ease_discard(mod, instant, silent)</ins>

__Inscryption__
- custom dollar change context

### <ins>Card:update(dt)</ins>

__Inscryption__
- Blueprint?'s transformation

### <ins>SMODS.current_mod.reset_game_globals(run_start)</ins>

__Inscryption__
- automatic run seeding
- Egg?'s effect

__4Fun__
- No Bitches?' unlock condition

### <ins>generate_card_ui(\_c, full_UI_table, specific_vars, card_type, badges, hide_desc, main_start, main_end, card)</ins>

__Inscryption__
- automatic Jokester descriptions

### <ins>Card:add_to_deck(from_debuff)</ins>

__The Binding of Isaac__
- Moriah's unlock condition

__Inscryption__
- automatic sticker application

### <ins>Card:set_cost()</ins>

__Inscryption__
- Astronomer?'s effect
- Ijiraq's Astronomer effect

### <ins>SMODS.four_fingers()</ins>

__Inscryption__
- Four Fingers?

### <ins>SMODS.shortcut()</ins>

__Inscryption__
- Shortcut?

### <ins>G.UIDEF.use_and_sell_buttons(card)</ins>

__Inscryption__
- Perkeo?'s button rendering

### <ins>Card:highlight(is_higlighted)</ins>

__Inscryption__
- Perkeo?'s button rendering

### <ins>get_new_boss()</ins>

__Inscryption__
- Pareidolia?'s effect

### <ins>Game:update(dt)</ins>

__4Fun__
- No Bitches?' effect

### <ins>love.draw()</ins>

__4Fun__
- No Bitches?' effect
