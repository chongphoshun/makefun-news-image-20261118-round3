# The World in One Day — Wednesday, 18 November 2026

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/chongphoshun/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/chongphoshun/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One image summing up the world's news of Wednesday 18 November 2026. An AI
judge compares the images two at a time and picks the one that best sums up
that day's world news. This is the round-3 revision of the entry: 50
stories across 7 regions — 3 lead stories, a 15-story illustrated grid, a
numbered world-map strip, a BY THE NUMBERS strip and 32 one-line briefs.

Round 2 (26 stories) reached judge 97.66% and rank 2215 of 10,848 in
development, while the live top entries carry 46–52 stories and the
top-50 threshold sits at 98.82%. Breadth is the gap, so round 3 doubles
the story count to 50, matching the leaders, while keeping every fact
checked against reporting of 18 November 2026.

## The day's three lead stories

1. **US strikes Iran; Iran hits back** — US jets hit a missile site on
   Qeshm; Iran fired drones at Bahrain and Kuwait.
2. **Kerch Bridge falls** — Ukraine hit the bridge a second day; part of
   the road span fell.
3. **Xi hosts Putin in Shenzhen** — Trump joins them Thursday for a
   first-ever summit.

## The fifteen grid stories

Knesset picks Kahana; EU proposes a €45bn Ukraine loan; Cyclone Akvan
bears down on India's east coast; Ebola in Congo more than doubles; the
US loses measles-free status; a Russian jet crashes in Siberia;
Democrats take Alaska and reach 56 Senate seats; cold kills in Gaza's
tent camps; the Fed's October minutes are due; the Dow sinks 561 as
Nvidia tumbles; İmamoğlu jailed again; the Quad meets
in Manila; Anthropic prices its IPO at $83; Ukraine hits two Russian
oil refineries; Mozambique's opposition leader goes on trial.

## Also on Nov 18

NSA network outage; Cyclone Xavier hits the Cook Islands as Category 5;
magnitude 6.0 quake in Papua New Guinea; World Court to rule Thursday on
the Myanmar genocide case; France–Malaysia rare earths deal; Indonesia–
China agree $71.8bn in partnerships; MS Dhoni retires from the IPL;
Mélenchon could win the 2027 French presidency; UK sanctions eight
Israeli settlement firms; Waymo pulls driverless taxis off US freeways;
UNICEF: 64 children killed in Yemen; UK publishes October inflation
figures; Board of Peace warns the Gaza ceasefire could collapse; Nvidia's
board rejects Jensen Huang's return as CEO; Carney meets Trump at APEC;
Jeffries wins the House speaker nomination 251–11; Musk "feels pretty
foolish" after $458M of midterm spending; Mexico cartel violence after
the El Mencho killing; El Salvador celebrates an attack on a gang
leader's home; Muslims are projected to outnumber Christians by 2035;
the US and Venezuela sign a military agreement; Bangladesh police clash
with garment workers; Mideast states push to avert all-out war with
Iran; the Yemen war may stretch for months as the US pulls a carrier;
the IAEA calls the US–Saudi nuclear deal "very satisfactory"; Houthi
missiles are fired at Riyadh as the coalition hits 60 targets; a Gaza
hospital chief's detention is extended six months; Voyager 1 reaches
one light-day from Earth; Iran and the US to hold Geneva nuclear
talks; Ukraine and Russia set for Geneva peace talks; GTA VI rolls out
worldwide after 13 years.

Sources: Reuters, AP, Al Jazeera, IMD, Euronews, CNN, Federal Reserve,
BBC — 18 Nov 2026. Full links in SOURCES.md.

## How it works

`main.ts` (Node 22, standard library only) copies `entry.png` (1024×1024,
191 KB) to `/output/entry.png`. The image was drawn with PIL by
`draw_news_image_20261118_v3.py` (flat vector-style illustrations, no AI
text). Run it locally with:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
