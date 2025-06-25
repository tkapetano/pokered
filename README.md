# Pokémon Red and Blue [![Build Status][ci-badge]][ci]

This is a disassembly of Pokémon Red and Blue.

It builds the following ROMs:

- Pokemon Red (UE) [S][!].gb `sha1: ea9bcae617fdf159b045185467ae58b2e4a48b9a`
- Pokemon Blue (UE) [S][!].gb `sha1: d7037c83e1ae5b39bde3c30787637ba1d4c48ce2`
- BLUEMONS.GB (debug build) `sha1: 5b1456177671b79b263c614ea0e7cc9ac542e9c4`
- dmgapae0.e69.patch `sha1: 0fb5f743696adfe1dbb2e062111f08f9bc5a293a`
- dmgapee0.e68.patch `sha1: ed4be94dc29c64271942c87f2157bca9ca1019c7`

To set up the repository, see [**INSTALL.md**](INSTALL.md).


## See also

- [**Wiki**][wiki] (includes [tutorials][tutorials])
- [**Symbols**][symbols]
- [**Tools**][tools]

You can find us on [Discord (pret, #pokered)](https://discord.gg/d5dubZ3).

For other pret projects, see [pret.github.io](https://pret.github.io/).

[wiki]: https://github.com/pret/pokered/wiki
[tutorials]: https://github.com/pret/pokered/wiki/Tutorials
[symbols]: https://github.com/pret/pokered/tree/symbols
[tools]: https://github.com/pret/gb-asm-tools
[ci]: https://github.com/pret/pokered/actions
[ci-badge]: https://github.com/pret/pokered/actions/workflows/main.yml/badge.svg


## Personal change log
 cp pokered.gbc ~/Documents/GBC/own_mods/pokered_v1.gbc

pokered_v1: 
- quicker walking , works

pokered_v2:
- starters are birds, works - but text is wrong and Rival still has normal starter
- tried changing the title but it is not simple text

pokered_v3:
- adapted some text
- renamed PROF.OAK to MC.OAK
- adapted rivals team, works now

pokered_v4:
- Encounter changes: replace 1% encounter pokemon by a nice one
- Plan make Catch'em all possible, by catch + evolve in a single game, traditionally 27/151 are not obtainable: 
    - mix the red / blue version specifics:
    blue: exclusive Pokémon are Sandshrew, Sandslash, Bellsprout, Weepinbell, Victreebel, Meowth, Persian, Vulpix, Ninetales, Magmar, and Pinsir.
    red: exclusive Pokémon are Ekans, Arbok, Oddish, Gloom, Vileplume, Mankey, Primeape, Growlithe, Arcanine, Scyther, and Electabuzz

    - all starters are catchable: Bulbasaur, Charmander, Squirtle
    CHARMANDER i
    CHARMELEON i
    CHARIZARD ii
    SQUIRTLE i
    WARTORTLE ii
    BLASTOISE i
    BULBASAUR i
    IVYSAUR i
    VENUSAUR ii

    - make evolve-on-trading pokemon catchable: Alakazam, Macham, Golem, Gengar
    (see v6, made them to evolve by level, not by trade)
    ALAKAZAM ii
    MACHAMP i
    GOLEM i
    GENGAR iiii

    - make choice pokemon catchable: Vaporeon, Jolteon, Flareon, Omanyte, Kabuto, Hitmonlee, Hitmonchan
    - HITMONLEE i
    - HITMONCHAN ii
    - OMANYTE ii
    - KABUTO ii
    - FLAREON i
    - JOLTEON iii
    - VAPOREON i

    - make Mew catchable
    - MEW ii

- spice up the 1% catch slot for a bigger variety of interesting pokemon to catch (in increasing niceness)
    - TANGELA i
    - ABRA ii
    - EEVEE ii
    - PONYTA i
    - RHYDON i
    - EXEGGCUTE ii
    - VULPIX ii
    - PIKACHU ii
    - LICKITUNG ii
    - PORYGON iii
    - TAUROS i
    - KANGASKHAN i
    - CHANSEY ii
    - MR_MIME ii
    - MAGMAR ii
    - ELECTABUZZ i
    - SCYTHER i
    - PINSIR ii
    - AERODACTYL ii
    - DRATINI iii
    - LAPRAS i
    - GYARADOS i
    - SNORLAX i

- distribute over the ca 60 span fields

pokered_v5:
- changed parties of some trainers
- changed some team rocket text
- made Team rocket stronger
- evolve by level not by exchange
- rival get mew and add hint