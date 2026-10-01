# Growth Audit — Praktika (volume 2)

**Live:** https://bterzic123.github.io/praktika-flow-rebuild-v2/

Five ideas to unlock more revenue from the traffic Praktika already has. A clickable prototype of the onboarding and paywall comes with it, rebuilt in Praktika's current design: the purple, the grey rows, the 3D level codes, Skye's Quick Chat and correction sheet, the study plan and the plan cards. Only the order of the screens changes.

Open it on a phone and it runs full-screen. The prototype has English, Spanish and Brazilian Portuguese, light and dark, and a 30-second walkthrough.

## The five ideas

| # | Idea | Screen | Potential outcome |
|:-:|:--|:--|:--|
| 01 | Offer your 3-month promo when they close | Offer on close | ARPU +10–15% |
| 02 | Name their goal on the paywall | Paywall | CR +15–20% |
| 03 | Ask for permissions after the paywall | Quick Chat | CR +10–15% |
| 04 | Put 4.7 stars and 30M+ learners by the button | Paywall | CR +10–15% |
| 05 | Take the rating request out of the loader | Loader | CR +8–12% |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps. They are not measured lift for Praktika.

## Where the numbers come from

Every price, rating, quote and feature line comes from Praktika's own published material:

- **App Store:** 4.7 stars from 165K ratings, the review quoted on the paywall, and the 3-Month Promo at $19.99.
- **praktika.ai:** 30M+ learners and 100K+ five-star reviews.
- **The app's own paywall:** $99.99 a year with one week free, $8 a month, the 3-month plan at $12 a month, and "50x cheaper than a tutor".
- **Artwork and chat:** the tutor portraits, the chat lines and the correction example are from praktika.ai and the App Store screenshots.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Volume 1 stays live at https://bterzic123.github.io/praktika-flow-rebuild/.
