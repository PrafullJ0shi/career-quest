# Career Quest

A terminal quest game in C where the treasure is a job offer.

## V2 roadmap

The game is not released yet; this repository holds its description. This is the plan for the version after the first playable release: planned, not shipped. The game stays a small, open-source C program; optional paid extras never lock the core game.

1. **Real listings as quests.** Load a cached copy of [Rolepool](https://github.com/PrafullJ0shi/rolepool)'s public `jobs.json`, or any feed in the same shape, and turn each posting into a quest with its company, role, level and skills. Every quest links to the real posting. *Players:* explore the actual job market while playing.
2. **Interview rounds as puzzles.** Short terminal challenges for each round: a regex to write, a git history to fix, an SQL query, a bug to find in ten lines of C. *Players:* practise skills that interviews really test.
3. **Daily seed run.** One shared world per day, the same for everyone, ending in a one-line result that can be shared without spoilers. *Players:* a reason to return each day and compare.
4. **Quest pack format.** Plain-text packs that add companies, puzzles and story without recompiling. *Developers:* write content in a text editor; packs are reviewed and loaded at run time.
5. **Play over SSH and in the browser.** An SSH server mode so anyone can play with `ssh`, and a WebAssembly build in a browser terminal. *Players:* no install. *Developers:* one C codebase, three ways to run.
6. **Skill map from play.** Cleared puzzles map to real skills, with links to learning material and to real listings that ask for them. Clearly a practice record, not a certificate. *Players:* see what to study next.
7. **Sponsored challenges.** Employers can host a real, clearly labelled challenge level with a link to their posting; no player data is shared without the player opting in. *Revenue:* sponsors pay per challenge season.
8. **Supporter edition.** Pay-what-you-want builds and extra story packs on an indie games store, while the open-source game stays complete and free. *Revenue:* direct support from players.
9. **Saves, colours and accessibility.** Portable save files, a no-colour mode, a screen-reader-friendly mode and full keyboard play. *Players:* comfortable on any terminal.
10. **Learn C from the game.** The source is organised as a readable track (state machine, parsing, file I/O, memory) with exercises that change the game. *Developers and learners:* a real program to study. *Revenue:* an optional companion workbook.

**Order.** V2.0: items 1, 2, 3, 4 and 9. V2.1: items 5, 6, 7, 8 and 10.
