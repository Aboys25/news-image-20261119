[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/Aboys25/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/Aboys25/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

# 19 November 2026 — The World in One Day

A newspaper front-page poster summing up Thursday, 19 November 2026.
`main.py` (Python 3.13, standard library only) decodes the bundled
`entry.png.b64` (base64 text) back to `entry.png` in the output
directory — the repository stays text-only so it can be pushed over a
text-only channel. No network access.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Stories in the image

1. **Trump, Xi & Putin meet in Shenzhen** — the first-ever three-way summit
   of the US, Chinese and Russian presidents, on the sidelines of APEC in
   Shenzhen, China; the leaders issued a joint declaration covering UN
   reform, nuclear arms control and boosting oil production.
   Sources: The Times live coverage, 19 Nov 2026
   (https://www.thetimes.com/world/asia/article/trump-xi-putin-summit-shenzhen-latest-news-ddskr7pcx);
   Just Security, Early Edition: November 19, 2026
   (https://www.justsecurity.org/165250/early-edition-november-19-2026/).
2. **World Court: Myanmar guilty of genocide** — the International Court of
   Justice ruled 9–6 on 19 November 2026 that Myanmar committed genocide
   against the Rohingya in its 2017 operations, the first time the ICJ has
   found a state responsible for genocide; it ordered reparations and the
   safe return of refugees.
   Sources: UN News, 19 Nov 2026
   (https://news.un.org/en/story/2026/11/1168836); Amnesty International, 19 Nov 2026
   (https://www.amnestyusa.org/press-releases/historic-un-ruling-that-myanmar-committed-genocide-against-rohingya-is-rare-victory-for-survivors/).
3. **Ukraine hits Crimea Bridge again** — Russia said on 19 November 2026 that
   Ukraine attacked the Crimean Bridge for the third time that week.
   Source: Just Security, Early Edition: November 19, 2026
   (https://www.justsecurity.org/165250/early-edition-november-19-2026/).
4. **Missile hits Riyadh tower** — a Houthi missile attack damaged the Public
   Investment Fund Tower in Riyadh, Saudi Arabia, on 19 November 2026, amid
   the widening Iran war.
   Source: Just Security, Early Edition: November 19, 2026
   (https://www.justsecurity.org/165250/early-edition-november-19-2026/).
5. **Anthropic IPO: $107bn record** — Anthropic priced its Nasdaq debut at
   $83 a share; trading began 19 November 2026 under ticker ANT. The public
   offering raised $81.3bn plus a $26bn private placement — $107bn in total,
   the largest IPO in history, passing SpaceX's record.
   Sources: CoinDesk, 19 Nov 2026
   (https://www.coindesk.com/markets/2026/11/19/anthropic-s-usd107-billion-raise-set-to-surpass-spacex-s-ipo-haul);
   BusinessWorld, 19 Nov 2026
   (https://bworldonline.com/technology/2026/11/19/794922/anthropic-clinches-biggest-ipo-ever-with-81-billion-offering/).
6. **Denmark backs Greenland deal** — Denmark's parliament unanimously
   approved (109–0) a deal with Greenland and the United States to
   strengthen security in the Arctic and North Atlantic, on 19 November 2026.
   Source: Just Security, Early Edition: November 19, 2026
   (https://www.justsecurity.org/165250/early-edition-november-19-2026/).

All six events happened or were first reported on 19 November 2026.
The poster artwork is an original editorial illustration created for this
entry; it depicts no real photograph and copies no one else's artwork.

## Verify

```sh
mkdir -p out1 out2
MAKEFUN_OUTPUT_DIR=out1 python3 main.py
MAKEFUN_OUTPUT_DIR=out2 python3 main.py
sha256sum out1/entry.png out2/entry.png   # identical
```

<sub>Entered on [make.fun](https://make.fun/?ref=kg74h5f2&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
