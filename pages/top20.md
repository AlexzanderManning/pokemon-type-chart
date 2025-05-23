---
layout: top20
permalink: /top20
title: Pokémon Gen 6+ Type Matchup Chart
description: Shows how damage modifiers are applied when attacking and defending against Pokémon of different types in Pokémon Generation 6+ games
lang: en
pokemon:
  -
    name: "Calyrex-Shadow"
    img: "https://img.pokemondb.net/sprites/scarlet-violet/normal/calyrex-shadow-rider.png"
    type: "psychic"
    damage_from:
      -
        amount: "quad"
        types: [ 'dark', "ghost" ]
      -
        amount: "half"
        types: [ "poison", "psychic" ]
      -
        amount: "immune"
        types: ['fight', 'normal' ]
    damage_to:
      -
        amount: "double"
        types: ['fight', 'ghost', 'poison', 'psychic']
      -
        amount: "half"
        types: [ 'dark' ]
  -
    name: "Urshifu-Rapid-Strike"
    img: "https://img.pokemondb.net/sprites/scarlet-violet/normal/1x/urshifu.png"
    type: "fight"
    damage_from:
      -
        amount: "double"
        types: [ "elec", "fairy", "flying", "grass", "psychic" ]
      -
        amount: "half"
        types: [ "bug", "dark", "fire", "ice", "rock", "water", "steel" ]
    damage_to:
      -
        amount: "double"
        types: [ 'dark', 'fire', 'ground', 'ice', 'normal', 'rock', 'steel' ]
  -
    name: "Miraidon"
    img: "https://img.pokemondb.net/sprites/home/normal/miraidon.png"
    type: "dragon"
    damage_from:
      -
        amount: "double"
        types: [ "dragon", "fairy", "ice", "ground" ]
      -
        amount: "half"
        types: [ "elec", "grass", "fire", "flying", "water",  "steel"]
    damage_to:
      -
        amount: "double"
        types: [ "flying", "water", "dragon" ]
  -
    name: "Zamacenta"
    img: "https://img.pokemondb.net/sprites/go/normal/zamazenta-crowned.png"
    type: "fight"
    damage_from:
      -
        amount: "double"
        types: ["fairy", 'flying', 'psychic' ]
      -
        amount: "half"
        types: [ 'bug', 'dark', 'rock']
    damage_to:
      -
        amount: "double"
        types: [ 'dark', 'ice', 'normal', 'rock', 'steel' ]
      -
        amount: "half"
        types: [ 'bug', 'fairy', 'flying', 'poison', 'psychic']
      -
        amount: "immune"
        types: [ "ghost" ]
  -
    name: "Rillaboom"
    img: "https://img.pokemondb.net/sprites/go/normal/rillaboom.png"
    type: "grass"
    damage_from:
      -
        amount: "double"
        types: ['bug', 'fire', 'flying', 'ice', 'poison' ]
      -
        amount: "half"
        types: ['elec', 'grass', 'ground', 'water']
    damage_to:
      -
        amount: "double"
        types: [ 'ground', 'rock', 'water' ]
      -
        amount: "half"
        types: ['bug', 'dragon', 'fire', 'flying', 'grass','poison', 'steel']
---
