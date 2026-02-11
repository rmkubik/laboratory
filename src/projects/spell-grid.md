---
publishedAt: 2026-02-08
title: Spell grid
description: An arcane programming game
---

I like programming games, [Zachtronics](https://www.zachtronics.com/) in particular. I also really like [Gestalt_OS](https://games.increpare.com/Gestalt_OS/).

I've been curious about what a 2D [esolang](https://esolangs.org/wiki/Esoteric_programming_language) would be like to work with. I thought it could make a good base for a programming game.

Thematically, I'd like to cast this game as a sort of "scientific" spell casting game. [Opus Magnum](https://www.zachtronics.com/opus-magnum/) does this theme well, and I was inspired by reading [Blood Over Bright Haven](https://www.penguinrandomhouse.com/books/755073/blood-over-bright-haven-by-m-l-wang/) recently. I found its depiction of magic really interesting, and I could kind of imagine it as programming.

I'd like to make a version of this project where the different instructions are represented by arcane runes or symbols. Instead of the traditional Zachtronics PDF instructions, you'd have scrolls and tomes and other cryptic documents to pore through.

<iframe src="https://rk-spell-grid.netlify.app/" style="width: 100%; height: 100%;"></iframe>

---

## 2/10/26

None of that cool stuff exists in the current prototype! I had some fun making the base 2D programming environment. I found it tricky to come up with good instructions that felt like they could be puzzle pieces.

I think I would need to create instructions that have orthogonal mechanics. There shouldn't be an instruction that just lets you change your direction downward. Instead, it should turn your direction based on how much flux there is, generate mana based on the next instruction, and do something else even.

I think I need more mechanics in this game to play with to fill out that "something else". I need another resource, but ideally something more interesting than just "a resource".
