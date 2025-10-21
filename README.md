# List of PS sim PRs

## Other people’s PRs

| PR | Difficulty (1-4) | Reviewed by | Notes |
| --- | ---: | --- | --- |
| [Fix Doom Desire and Future Sight animation bugs](https://github.com/smogon/pokemon-showdown/pull/11382) | 1 | hydra | |
| [Gen 3: Remove Tickle from King's Rock list](https://github.com/smogon/pokemon-showdown/pull/11479) | 1 | hydra | |
| [Prevent Bug Bite from eating Jaboca Berry in gens 5-9](https://github.com/smogon/pokemon-showdown/pull/11363) | 1 | hydra, urkerab | Merge conflicts |

## Karthik PRs
| PR |
| --- |
| [Fix interaction between Receiver and Soul-Heart](https://github.com/smogon/pokemon-showdown/pull/11299) |
| [Refactor move accuracy modifiers](https://github.com/smogon/pokemon-showdown/pull/11263) |

## My PRs

I didn’t include PRs that are currently blocked by other PRs.

### Difficulty 1 - just merge it
| PR | Reviewed by | Notes |
| --- | --- | --- |
| [Standardize action orders](https://github.com/smogon/pokemon-showdown/pull/11340) | | I just submitted this because I was making the same changes in multiple PRs |
| [Dynamax Pokemon should be affected by Taunt](https://github.com/smogon/pokemon-showdown/pull/11361) | | One line |
| [Unskip Fling + Leppa Berry test](https://github.com/smogon/pokemon-showdown/pull/10904) | | Just tests |
| [Fix Round order prioritization and boosting logic](https://github.com/smogon/pokemon-showdown/pull/10915) | | |
| [Add test for Metal Burst + berries interaction in Gen 4](https://github.com/smogon/pokemon-showdown/pull/11152) | | Just tests. Don't merge yet. I should add another test for Counter + berries |
| [Add Switch Priority Clause Mod to Gen 1 and Gen 2 formats](https://github.com/smogon/pokemon-showdown/pull/11262) | | Meh, bureaucracy |
| [Fix interaction between Emergency Exit and Substitute](https://github.com/smogon/pokemon-showdown/pull/11350) | | Simple obscure bug |
| [Fix Mold Breaker interaction with Dark and Fairy Aura](https://github.com/smogon/pokemon-showdown/pull/11370) | | |
| [Fix Throat Spray activation message after opponent faints](https://github.com/smogon/pokemon-showdown/pull/11489) | | |
| [Just tests](https://github.com/smogon/pokemon-showdown/pull/11493) | | Just tests |

### Difficulty 2 - quick 2-minute review, should be a merge
| PR | Reviewed by | Notes |
| --- | --- | --- |
| [Fix Order Up's interaction with Sheer Force](https://github.com/smogon/pokemon-showdown/pull/10891) | | |
| [Implement Dancer using the battle queue](https://github.com/smogon/pokemon-showdown/pull/10975) | pyuk | Implemented existing TODO comments |
| [Fix crystal-free Z-Moves and Dynamax-less Max Moves](https://github.com/smogon/pokemon-showdown/pull/11090) | | Simple PR with all the sources, just needs attention |
| [Fix Synchronize and Toxic Spikes interaction in Gen 4](https://github.com/smogon/pokemon-showdown/pull/11186) | Slayer | |
| [Fix Psycho Shift effect timing in Gen 4](https://github.com/smogon/pokemon-showdown/pull/11196) | Slayer | |
| [Fix Klutz's interactions with non-held activated items](https://github.com/smogon/pokemon-showdown/pull/11204) | | Large but simple |
| [Fix Klutz's interaction with Iron Ball in Gen 4](https://github.com/smogon/pokemon-showdown/pull/11205) | Slayer | Simple, but the implementation looks a bit weird |
| [Remove partiallyTrapped if the source faints later during residuals](github.com/smogon/pokemon-showdown/pull/11285) | | |
| [Redirect the Counter target if the original one has fainted](https://github.com/smogon/pokemon-showdown/pull/11383) | | |
| [Counter should be callable by Sleep Talk](https://github.com/smogon/pokemon-showdown/pull/11384) | | |

### Difficulty 3 - mechanically sound, but review carefully
| PR | Reviewed by | Notes |
| --- | --- | --- |
| [Fix spread move reduction in Gen 4](https://github.com/smogon/pokemon-showdown/pull/11180) | Slayer, Zarel | |
| [Fix gen 3 switch in order](https://github.com/smogon/pokemon-showdown/pull/11185) | | Implemented with Marty's input and they already tested it |
| [Implement field- and all-target moves](https://github.com/smogon/pokemon-showdown/pull/11211) | Slayer, urkerab | Very good and sound refactor, but it is a bit big. Has a small client PR attached |
| [Remove Prankster hints](https://github.com/smogon/pokemon-showdown/pull/11302) | | Reviewed by Slayer and Zarel with no concrete conclusion |
| [Fix Xerneas formes](https://github.com/smogon/pokemon-showdown/pull/11369) | | Simple PR, mechanically sound. Marty and Zarel are worried with replay backward compatibility |
| [Refactor of Neutralizing Gas and multiple ability fixes](https://github.com/smogon/pokemon-showdown/pull/11373) | | Implemented with Karthik's input. They said they would review it when they had time |
| [Implement Ruin Abilities as field effects](https://github.com/smogon/pokemon-showdown/pull/11371) | | Approved mechanics, implementation needs review. The methods names are awful |
| [Normalize the implementation of Generational Mechanics](https://github.com/smogon/pokemon-showdown/pull/11509) | Slayer | |

### Difficulty 4 - involves dubious events, probably needs a DaWoblefet review
| PR | Reviewed by | Notes |
| --- | --- | --- |
| [Fix the timing of Unnerve and Neutralizing Gas with self-switching moves](https://github.com/smogon/pokemon-showdown/pull/11347) | | I would like to see this merged ASAP because I have 3 PRs in draft that depend on it. Karthik told me that they wanted DaWoblefet's input |
| [Fix Symbiosis' interactions with Eject Pack and Power Herb](https://github.com/smogon/pokemon-showdown/pull/10898) | | My solution is purely empirical, but it works correctly for all examples |
