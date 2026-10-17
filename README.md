<div align="center">

<img src="assets/logo.svg" alt="Pixel heart logo" width="120" />

# FLAMES Calculator

For the names we scribbled in notebooks<br>and the crushes we never confessed.

<a href="https://flames-calculator-swart.vercel.app"><img src="https://img.shields.io/badge/live-flames--calculator--swart.vercel.app-f0809a?style=flat-square&labelColor=2b1b22" alt="Live demo" /></a>
<a href="https://github.com/saijishnup/flames-calculator/blob/main/LICENSE"><img src="https://img.shields.io/github/license/saijishnup/flames-calculator?style=flat-square" alt="MIT License" /></a>
<img src="https://img.shields.io/badge/single%20file-HTML-ffb3c6?style=flat-square&labelColor=2b1b22" alt="Single HTML file" />
<img src="https://img.shields.io/badge/dependencies-0-d9ccff?style=flat-square&labelColor=2b1b22" alt="Zero dependencies" />
<a href="https://buymeatea.in/saijishnup"><img src="https://img.shields.io/badge/buy%20me%20a-tea-ffe9b8?style=flat-square&labelColor=2b1b22" alt="Buy Me a Tea" /></a>

</div>

---

## What it is

FLAMES is the school-days game: write two names, strike out the letters they share, count what is left, and walk that count around **F · L · A · M · E · S** until one letter survives.

| Letter | Meaning |
| :---: | --- |
| **F** | Friends |
| **L** | Lovers |
| **A** | Affection |
| **M** | Marriage |
| **E** | Enemies |
| **S** | Siblings |

This version plays the whole thing out for you, one step at a time.

## Features

- **Animated working.** Shared letters pair up and strike off, the leftovers are counted, then the F‑L‑A‑M‑E‑S tiles spin and drop out one by one.
- **Sound.** A bubble pop on Calculate, a soft whoosh on Clear, a tick for every step of the spin and a chime for the result. One tap mutes it all.
- **Speed control.** Slow, Normal or Fast, changeable mid‑animation.
- **Result card.** Falling translucent hearts, plus a share button that turns the result into an image for WhatsApp, Telegram, X or your phone's own share sheet.
- **Living background.** Pastel colours drift on their own and follow your cursor across the empty background.
- **Built for phones.** Large tap targets, no sideways scrolling, and respect for reduced‑motion settings.

## How the count works

Take **Ananya** and **Rohan**:

```
ananya   →  a̶ n̶ a n y a        (one a and one n are shared)
rohan    →  r o h a̶ n̶
left over:  a n y a  +  r o h  =  7 letters

Count 7 around the wheel, strike where you land, keep counting from the next letter:
F L A M E S  →  strike F
L A M E S    →  strike A
L M E S      →  strike S
L M E        →  strike L
M E          →  strike M
last letter standing: E  →  Enemies
```

Names are lowercased, accents are dropped, and anything that is not a letter is ignored. Two identical names leave nothing to count, so the game falls back to **F**.

## Run it locally

No build step. Download or clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/saijishnup/flames-calculator.git
cd flames-calculator
open index.html        # or double-click it
```

## The original C version

This started as a command-line program in C. It lives on in the [`c-version`](https://github.com/saijishnup/flames-calculator/tree/c-version) branch.

## Privacy

Everything runs in your browser. Names are never sent anywhere, saved, or logged. There are no cookies, accounts or analytics. Fonts load from Google Fonts. The full policy is linked in the app's footer.

## Support

If FLAMES made you smile, you can [buy Sai Jishnu P a coffee](https://buymeatea.in/saijishnup). It goes through UPI with zero commission, via Buy Me a Tea.

## License

[MIT](LICENSE) © 2026 Sai Jishnu P

<div align="center">
<sub>FLAMES is a playground game, not a prophecy.</sub>
</div>
