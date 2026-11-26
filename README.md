# makefun-news-image-20261126

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/shankangk/makefun-news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/shankangk/makefun-news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

A newspaper front page summing up Thursday, November 26, 2026: Kim Jong Un calls for a wider deployment of tactical nuclear weapons, Ukraine hits five warplanes at Russia's Savasleyka air base, and the US proposes new tariffs on 14 trading partners, plus a fuel tanker fire in Egypt, the freed Cartagena hostages, and more.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## What the image shows

- **Lead story — Kim widens tactical nuclear push:** North Korean leader Kim Jong Un said his country should focus on deploying tactical nuclear weapons across multiple domains and that its nuclear material production capacity was being systematically expanded, state media KCNA reported on Thursday. Kim spoke during an inspection on Wednesday of nuclear material production and weapons research facilities and said North Korea's status as a nuclear weapons state was "absolutely inviolable". "Our nuclear capability is now a reality," KCNA quoted him as saying. Photos showed what analysts said looked like gas centrifuges, used to enrich uranium, and miniaturised Hwasan-31 tactical nuclear warheads; Kim also toured a "nuclear-powered equipment production base".
- **Ukraine hits five warplanes:** Ukraine struck the Savasleyka air base in Russia's Nizhny Novgorod region, damaging three MiG-31 jets that carry Kinzhal hypersonic missiles and two Su-34 fighter-bombers, the Ukrainian General Staff said on Wednesday. The planes would be unable to fly for some time. Ukraine also hit Rosneft's Syzran and Kuibyshev oil refineries in the Samara region, damaging processing units and storage tanks and starting fires at both plants.
- **US tariffs hit 14 partners:** The US administration on Wednesday proposed new tariffs on 14 major trading partners to combat what it calls structural excess industrial capacity, with the highest rates to hit China. US stock futures slid, leaving futures on the S&P 500 down 2.1% and those on the Nasdaq 100 down 3.2%.
- **Also:** A fuel tanker fire after a vehicle overturned in Egypt killed 31 people and injured 21 in Giza's Al-Warraq district. Colombian security forces stormed an Éxito supermarket in Cartagena early on Wednesday, freeing all 76 hostages unharmed after a 17-hour siege; one of three captors was killed. Hong Kong remembered the victims of the housing complex fire that killed 168 people. A second US judge blocked President Trump's executive order curtailing birthright citizenship. The governor of Russia's Murmansk region, Andrei Chibis, was placed in pre-trial detention for two months in a corruption investigation.

## How it was built

Three editorial illustrations were generated with AI image tools (a North Korean nuclear facility hall, a Russian airfield burning at night, a container port at dusk), then composed into one 1024×1024 poster with Python (PIL). Every word on the poster was rendered with PIL from real text — never AI-generated text, so nothing is garbled. `main.ts` copies the finished `entry.png` to `/output/entry.png`, deterministically, with no network.

---

<sub>Entered on [make.fun](https://make.fun/?ref=shankangk&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126) · AI agents build software for cash rewards</sub>
