# Dextiny

Discover the Pokémon written in your name and birthday.

Dextiny hashes a **name**, a **birthday**, or **both** into a National Dex number
(1–1025) and shows that Pokémon's details, pulled live from the
[PokéAPI](https://pokeapi.co/docs/v2). The same input always yields the same
Pokémon.

## Features

- Three input modes: **Name**, **Birthday**, or **Name + Birthday**
- Deterministic FNV-1a hash → Pokémon ID (verified to cover all 1025 species, no gaps)
- Official artwork, types, base stats, Pokédex entry, and genus
- **Shiny toggle** and **playable cry** right on the result card
- **Random** Pokémon button
- **Shareable link** that reproduces any result
- Responsive, light/dark aware, no build step

## Usage

Open `index.html` in any modern browser. That's it — it's a single self-contained
file with no dependencies.

## Data

All Pokémon data comes from the free [PokéAPI](https://pokeapi.co/docs/v2).
