# Pokedex

## Commands

```eval_rst
.. csv-table:: Pokedex User Manual 
   :header: "Command", "Who", "Where", "Description"
   :widths: 15, 10, 10, 20

   ``$dex latios``, Anyone, Guild / DM, "Displays the pokedex page for latios."
   ``$pokedex latios``, Anyone, Guild / DM, "Displays the pokedex page for latios."
   ``$mdex smack down``, Anyone, Guild / DM, "Displays the movedex page for smack down."
   ``$movedex smack down``, Anyone, Guild / DM, "Displays the movedex page for smack down."
   ``$counters latios``, Anyone, Guild / DM, "Displays counters for latios in no weather."
   ``$counters latios windy``, Anyone, Guild / DM, "Displays counters for latios in windy weather."
```

## Features

### Looking Up Pokemon

Most Pokemon can be looked up using their standard english name. Names are case insensitive. At the moment, PokeNav only supports English language lookups:

`$dex snorlax`

#### Alolan Forms

`$dex raichu-alola`

In fact, all forms are always written in PokeNav as `pokemon-form`:

`$dex deoxys-attack`

This extends even to trade commands (which are covered more in [the trading section](trading.md)):

`$want unown-a`

#### Names With Punctuation and Spaces

If a Pokemon isn't recognized, try it without puntuation and with quotes if the name contains spaces:

`$dex "Mr Mime"`

<img src="/_static/imgs/mr_mime_dex.png" />
