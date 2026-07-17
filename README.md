# GYRE

*A first-person crypt-crawl card roguelike. Where you look is where you live.*

You are the **Warden** — you guard only the way you face. The dead circle the ring around you, sliding for your unguarded back. Strike them down and **tear their moves into your deck**: every real card you own was looted from something you killed.

## The hook — *facing is a weapon*
- Turn-based combat on a **compass ring**: you stand at the center, enemies occupy the 8 slots around you.
- Your guard covers the **front arc** (the slot you face + its two neighbours). A blow to your sides ignores block; a blow to your **back is a backstab**.
- **Turning is budgeted** — one free pivot per turn, then you spend cards. You can't cheaply face everyone.
- Enemies actively **flank** to get behind you. Rotate, or drag them back into your guard with the Hook.

## Play
- **Crawl:** `W`/`↑` step · `A` `D` (or `←` `→`) turn · `S` back
- **Fight:** click cards (or press `1`–`9`) · `A`/`D` rotate · `Space` ends your turn
- Descend three procedurally-generated floors of the Undercroft and silence the **Bellringer**.

New here? Hit **Learn the Ways** on the title for a guided tutorial.

## Tech
Single-file [Three.js](https://threejs.org/) (WebGL) + procedural WebAudio. No build step — just open `index.html`, or serve the folder statically.

Built with [Claude Code](https://claude.com/claude-code).
