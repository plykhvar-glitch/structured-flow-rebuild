# Growth Audit — Structured

**Live:** https://plykhvar-glitch.github.io/structured-flow-rebuild/
**Prototype only:** https://plykhvar-glitch.github.io/structured-flow-rebuild/?view=proto

Every new Structured install plans a whole day before the paywall: wake-up time, bedtime, a first task, its time, its length and its colour. The paywall that follows uses only the colour. This audit rebuilds the first launch in Structured's own design so Pro is sold on the day the user just planned, with all three plans in view.

Two views: an **Overview** with five ranked ideas, and a **Prototype** with three phones side by side (an install from the Meta ad, an ADHD planner from the App Store, a student). Light and dark, a 30-second walkthrough, and a QR code to open it on a phone.

## The five ideas

| # | Idea | Expected effect |
| :-- | :-- | :-- |
| 1 | Open Pro on the day they just planned: the headline takes their task and its time, the first rows of the Pro vs Free table follow the task | CR +15–20% |
| 2 | Ask what the day is for, with five answers from the App Store "Perfect for" list; it reorders the task suggestions and picks the paywall's headline, rows and review | CR +8–20% · ARPU +13–35% |
| 3 | Put Monthly and Lifetime next to Yearly, Yearly picked, with "$1.25 a month · 74% less than Monthly" | CR +5–15% · ARPU +10–15% |
| 4 | Let the wait read their day back before "Awesome! That's a great plan." | CR +10–15% |
| 5 | Ask for notifications on the timeline, after Pro, instead of between the plan and the paywall | CR +10–15% |

Closing the paywall (Skip For Now) goes straight to the timeline. There is no second paywall.

## Grounding

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for Structured.

- Screens, copy, the Pro vs Free rows, the trial timeline, the in-app reviews and the prices ($4.99 a month, $14.99 a year with a three-day free trial, $49.99 Lifetime): the Structured iOS onboarding and paywall as published on screensdesign.com (US storefront).
- 4.8 from 169K ratings, Editors' Choice, the audience and "Perfect for" lines, Replan, and the reviews by skc7 and kayflowerz: the US App Store listing, read 11 November 2026. Award art from the App Store screenshots.
- 500K+ Pro users, the lifetime-membership review and the hero photo: structured.app.
- The ad: Meta Ad Library, Structured - Daily Planner page, 26 January to 1 February 2026.
- $1.25 a month is $14.99 ÷ 12; 74% is 1 − $14.99 ÷ $59.88 (twelve months at $4.99).

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/.

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)
