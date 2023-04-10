# Pokémon FireRed and LeafGreen

[![Build Status][travis-badge]][travis]

[travis]: https://travis-ci.org/pret/pokefirered
[travis-badge]: https://travis-ci.org/pret/pokefirered.svg?branch=master

This is a disassembly of Pokémon FireRed and LeafGreen.

It builds the following ROMs:

* [**pokefirered.gba**](https://datomatic.no-intro.org/?page=show_record&s=23&n=1616) `sha1: 41cb23d8dccc8ebd7c649cd8fbb58eeace6e2fdc`
* [**pokeleafgreen.gba**](https://datomatic.no-intro.org/?page=show_record&s=23&n=1617) `sha1: 574fa542ffebb14be69902d1d36f1ec0a4afd71e`
* [**pokefirered_rev1.gba**](https://datomatic.no-intro.org/?page=show_record&s=23&n=1672) `sha1: dd5945db9b930750cb39d00c84da8571feebf417`
* [**pokeleafgreen_rev1.gba**](https://datomatic.no-intro.org/index.php?page=show_record&s=23&n=1668) `sha1: 7862c67bdecbe21d1d69ce082ce34327e1c6ed5e`

To set up the repository, see [INSTALL.md](INSTALL.md).


## See also

Other disassembly and/or decompilation projects:
* [**Pokémon Emerald**](https://github.com/fdeblasio/pokeemerald)


## Notes
Regex:
([A-Z])([A-Z]+)
$1\L$2

(_\("[A-Z])([A-Z]+)("\))
$1\L$2$3

(_\("[A-Z])([A-Z]+)([ -][A-Z])([A-Z]+)("\))
$1\L$2$3\L$4$5

## TODO
Expand move/ability/item name length and update names accordingly
Update stats, move power, movesets, etc. for new gens
Add Fairy
Nature stats
Physical/Special Split
Koichi/Clarine
Reorganize Index numbers to match Dex numbers (if possible)
Add new moves and abilities
Reusuable TMs (https://www.pokecommunity.com/showpost.php?p=9980343&postcount=7)
Running anywhere
Evolution moves
Trainers with different balls
Exp. All
https://www.pokecommunity.com/showthread.php?t=416647&page=1
Out of battle abilities
IV/EV checker
Breeding mechanics
Premier ball in shop
Lower case after first input in the naming screen (https://www.pokecommunity.com/showpost.php?p=10461987&postcount=343)
Catch EXP
Newer QOL items (mints, bottle caps, PP Ups in shops, etc.)
Evolution moves
Menu nickname/relearner
3 perfect IVs for legendaries
Hidden Power type/power
Pokemon Icons
X Sp. Def
EV berries
Poke BallS
