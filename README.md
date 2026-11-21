# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/Rahulboss7788/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/Rahulboss7788/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

One image summing up the world's news of Saturday 21 November 2026, drawn as a
single newspaper front page — *The Saturday Globe*. The lead story is the Russian
missiles that came down in south-eastern Poland during a huge overnight attack on
Ukraine, which Warsaw called a deliberate provocation as NATO scrambled jets.
Around it: the International Court of Justice's landmark ruling in the Myanmar
genocide case, COP31 climate talks in Turkey reaching their crunch stage with no
deal in sight, fresh arson attacks amid unrest in Bangladesh, young protesters
rallying across Europe over living costs and arms spending, Denmark accusing
Russian intelligence of a murder plot on Danish soil, and Cyclone Akvan crossing
India's Odisha coast — plus a ticker of the day's other headlines.

## The image

`entry.png` is a 1024×1024 PNG (under 1 MiB) rendered from `page.html`, a
self-contained front-page layout with a hand-drawn SVG map of the three impact
sites in Poland. Every story on the page was reported on 21 November 2026; no
quotes or facts are invented.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). It uses no
network, so two runs write byte-identical output.

## Files

- `main.ts` — the entrypoint; copies the image to the output directory.
- `entry.png` — the submitted image, 1024×1024.
- `page.html` — the front-page design the image was rendered from.
- `LICENSE` — MIT.
