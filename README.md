# news-image-20261124 — The World in One Page

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/iwanr94/news-image-20261124/blob/main/LICENSE)
[![GitHub repo size](https://img.shields.io/github/repo-size/iwanr94/news-image-20261124)](https://github.com/iwanr94/news-image-20261124)
[![GitHub last commit](https://img.shields.io/github/last-commit/iwanr94/news-image-20261124)](https://github.com/iwanr94/news-image-20261124/commits/main)

A single front-page image summing up Tuesday 24 November 2026 in world news,
built for the make.fun bounty
[news-image-20261124](https://make.fun/bounty/news-image-20261124)
("Sum up 24 November's world news in one image", $100 total, top 50).

## The stories

- **Lead — CLIMATE TALKS COLLAPSE:** COP31 in Antalya ends with no deal, the
  first major COP breakdown since Copenhagen 2009, after the EU rejected a
  text with no fossil-fuel language.
- **HUANG BACK AT NVIDIA:** Nvidia reinstates Jensen Huang as CEO after
  intervention by President Trump; shares jump about 31%.
- **WAR SPREADS TO THE SEAS:** Russian cargo ship Sparta II hit by drones in
  the Gulf of Finland and towed out of Finnish waters; a Russian corvette hit
  at Benghazi, Libya.
- **FACTORY FIRE IN INDONESIA:** At least 24 dead and about 30 missing after a
  fire at the PT Fonusa Agung Mulia candy factory in Cikande, Banten.
- **GAZA POISONED, REPORT WARNS:** A new Oxfam / Conflict and Environment
  Observatory report warns Gaza's air, soil and water are contaminated by
  explosive and incendiary weapons.
- **CHESS CROWN ON THE LINE:** The World Chess Championship opens in Geneva —
  defending champion Gukesh Dommaraju v challenger Javokhir Sindarov, the
  youngest title match ever.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR` (default `/output`) as `entry.png`.

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Sources

CNN / Bloomberg (COP31), Reuters (Indonesia factory fire, via TBS News),
AP / CNBC (Nvidia), Finnish Defence Forces / CNN (Sparta II),
Oxfam & CEOBS (Gaza), Chess.com / FIDE (World Chess Championship).
