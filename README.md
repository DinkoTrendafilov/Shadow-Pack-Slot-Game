# 🐺🦇 SHADOW PACK 🕷️🐦‍⬛

🎮 **Play the game:** [https://github.com/DinkoTrendafilov/Shadow-Pack-Slot-Game](https://github.com/DinkoTrendafilov/Shadow-Pack-Slot-Game)

---

Shadow Pack is a dark-themed slot game with 4 symbols on a 4×5 grid, where payouts are determined by the sum of the two most frequent symbols on screen — a unique **Top-2 Sum** mechanic instead of classic paylines. The game features an RTP of **95.98%**, medium volatility (**VI 5.55**), and a **32% hit frequency**, all verified through **500 million simulated spins**. It includes a Python simulation engine for mathematical analysis and a fully playable HTML/JS interface with sound, animations, gamble feature, and save/load.

---

## 📖 Game Overview

| Property | Value |
|---|---|
| **Symbols** | 🐺 🐦‍⬛ 🦇 🕷️ |
| **Grid** | 4 rows × 5 reels = 20 positions |
| **Mechanic** | Top-2 Sum (two most frequent symbols) |
| **RTP** | 95.98% |
| **House Edge** | 4.02% |
| **Volatility Index** | 5.55 (medium) |
| **Hit Frequency** | 31.97% (1 in 3.13) |
| **Max Win** | 1,000× bet |
| **Simulated Spins** | 500,000,000 |

---

## 🎰 Symbols & Probabilities

| Symbol | Name | Weight | Probability |
|--------|------|--------|-------------|
| 🐺 | Wolf | 5 | 25.00% |
| 🐦‍⬛ | Raven | 5 | 25.00% |
| 🦇 | Bat | 5 | 25.00% |
| 🕷️ | Spider | 5 | 25.00% |

All symbols are equally weighted.

---

## 💰 Payout Table

| Top-2 Sum | Probability | 1 in | Payout (× bet) |
|-----------|-------------|------|----------------|
| 10 | 1.067087% | 93.7 | 12× |
| 11 | 10.670869% | 9.4 | — |
| 12 | 28.053377% | 3.6 | — |
| 13 | 29.302546% | 3.4 | — |
| 14 | 18.976300% | 5.3 | 1× |
| 15 | 8.424070% | 11.9 | 2.5× |
| 16 | 2.734619% | 36.6 | 7× |
| 17 | 0.650442% | 153.7 | 20× |
| 18 | 0.108674% | 920.2 | 60× |
| 19 | 0.011444% | 8,738.5 | 342× |
| 20 | 0.000572% | 174,762.9 | 1,000× |

> **Note:** Sums 11, 12, and 13 are non-paying "near miss" outcomes.

---

## 📊 Theoretical RTP Breakdown

| Sum | Probability | Payout | Contribution | % of RTP |
|-----|-------------|--------|--------------|----------|
| 10 | 1.067087% | 12 | 12.805043% | 13.34% |
| 14 | 18.976300% | 1 | 18.976300% | 19.77% |
| 15 | 8.424070% | 2.5 | 21.060174% | 21.94% |
| 16 | 2.734619% | 7 | 19.142330% | 19.94% |
| 17 | 0.650442% | 20 | 13.008839% | 13.55% |
| 18 | 0.108674% | 60 | 6.520432% | 6.79% |
| 19 | 0.011444% | 342 | 3.913723% | 4.08% |
| 20 | 0.000572% | 1000 | 0.572204% | 0.60% |
| **TOTAL** | | | **95.999047%** | **100.00%** |

---

## 🔬 Simulation Results (500,000,000 spins)

### RTP Verification

| | Theoretical | Simulated | Difference |
|---|---|---|---|
| **RTP** | 95.999047% | **95.977121%** | **-0.0219%** |

The simulated RTP matches the theoretical value within **1 standard error** (SE = 0.0238%), confirming the correctness of the simulation engine.

### Top-2 Sum Distribution — Simulation vs Theoretical

| Sum | Sim Count | Sim % | Theo % | Diff % | 1 in (sim) |
|-----|-----------|-------|--------|--------|------------|
| 10 | 5,335,559 | 1.067112% | 1.067087% | +0.0000% | 93.7 |
| 11 | 53,355,779 | 10.671156% | 10.670869% | +0.0003% | 9.4 |
| 12 | 140,257,247 | 28.051449% | 28.053377% | -0.0019% | 3.6 |
| 13 | 146,543,867 | 29.308773% | 29.302546% | +0.0062% | 3.4 |
| 14 | 94,865,619 | 18.973124% | 18.976300% | -0.0032% | 5.3 |
| 15 | 42,113,922 | 8.422784% | 8.424070% | -0.0013% | 11.9 |
| 16 | 13,675,791 | 2.735158% | 2.734619% | +0.0005% | 36.6 |
| 17 | 3,249,409 | 0.649882% | 0.650442% | -0.0006% | 153.9 |
| 18 | 542,864 | 0.108573% | 0.108674% | -0.0001% | 921.0 |
| 19 | 57,029 | 0.011406% | 0.011444% | -0.0000% | 8,767.5 |
| 20 | 2,914 | 0.000583% | 0.000572% | +0.0000% | 171,585.4 |

### Key Metrics

| Metric | Value |
|--------|-------|
| Total Spins | 500,000,000 |
| Total Bet | 500,000,000 credits |
| Total Won | 479,885,607 credits |
| Zero-Win Spins | 340,156,893 (68.03%) |
| Winning Spins | 159,843,107 (31.97%) |
| Max Single Win | 1,000 credits (1,000× bet) |
| Std Deviation (σ) | 5.3243 |
| Mean (μ) | 0.9598 |
| Volatility Index (σ/μ) | 5.5475 |
| Max Win Streak | 17 |
| Max Loss Streak | 47 |

---

## 📈 Win-Size Distribution

| Range | Count | % | 1 in |
|-------|-------|---|------|
| 0× | 340,156,893 | 68.031% | 1.5 |
| 0–1× | 94,865,619 | 18.973% | 5.3 |
| 1–5× | 42,113,922 | 8.423% | 11.9 |
| 5–20× | 22,260,759 | 4.452% | 22.5 |
| 20–50× | 0 | 0.000% | inf |
| 50–100× | 542,864 | 0.109% | 921.0 |
| 100–500× | 57,029 | 0.011% | 8,767.5 |
| 500–1000× | 2,914 | 0.001% | 171,585.4 |

---

## 💀 Bankroll Survival Analysis

**Setup:** 1,000 players · 100 credits initial · 1 credit per spin · max 100,000 spins

| Spins | Alive | Busted | Survival % | Min | Median | Max |
|-------|-------|--------|------------|-----|--------|-----|
| 100 | 1,000 | 0 | 100.00% | 27.00 | 86.75 | 487.00 |
| 200 | 995 | 5 | 99.50% | 1.00 | 80.00 | 518.00 |
| 300 | 918 | 82 | 91.80% | 1.00 | 79.00 | 1,027.50 |
| 400 | 798 | 202 | 79.80% | 1.50 | 81.75 | 1,017.00 |
| 500 | 706 | 294 | 70.60% | 1.00 | 86.00 | 1,076.00 |
| 600 | 629 | 371 | 62.90% | 1.00 | 94.00 | 1,392.50 |
| 700 | 568 | 432 | 56.80% | 4.00 | 93.00 | 1,415.00 |
| 800 | 512 | 488 | 51.20% | 1.50 | 102.50 | 1,429.00 |
| 900 | 462 | 538 | 46.20% | 1.00 | 114.00 | 1,449.00 |
| 1,000 | 416 | 584 | 41.60% | 3.50 | 119.25 | 1,486.00 |
| 1,500 | 303 | 697 | 30.30% | 2.50 | 149.00 | 1,421.50 |
| 2,000 | 234 | 766 | 23.40% | 1.50 | 161.00 | 1,391.50 |
| 2,500 | 193 | 807 | 19.30% | 2.50 | 215.00 | 1,590.50 |
| 5,000 | 102 | 898 | 10.20% | 4.50 | 307.50 | 1,980.00 |
| 10,000 | 47 | 953 | 4.70% | 24.50 | 593.50 | 2,023.50 |
| 25,000 | 19 | 981 | 1.90% | 82.00 | 712.00 | 2,109.00 |
| 50,000 | 5 | 995 | 0.50% | 497.00 | 1,523.50 | 2,572.00 |
| 75,000 | 2 | 998 | 0.20% | 311.00 | 1,627.25 | 2,943.50 |
| 100,000 | 1 | 999 | 0.10% | 1,458.00 | 1,458.00 | 1,458.00 |

### Survival Summary

| After | Alive | Rate | Busted | Min/Med/Max |
|-------|-------|------|--------|-------------|
| 100 spins | 1,000 | 100.00% | 0 | 27.00 / 86.75 / 487.00 |
| 500 spins | 706 | 70.60% | 294 | 1.00 / 86.00 / 1,076.00 |
| 1,000 spins | 416 | 41.60% | 584 | 3.50 / 119.25 / 1,486.00 |
| 2,500 spins | 193 | 19.30% | 807 | 2.50 / 215.00 / 1,590.50 |
| 5,000 spins | 102 | 10.20% | 898 | 4.50 / 307.50 / 1,980.00 |
| 10,000 spins | 47 | 4.70% | 953 | 24.50 / 593.50 / 2,023.50 |
| 25,000 spins | 19 | 1.90% | 981 | 82.00 / 712.00 / 2,109.00 |

---

## 💵 Financial Breakdown

| | Value |
|---|---|
| Total Bet | 500,000,000 credits |
| Total Paid Out | 479,885,607 credits (95.98%) |
| Company Profit | 20,114,393 credits |
| House Edge | 4.02% |

### Scaled Profit Scenarios

| Bet Size | Profit | House Edge |
|----------|--------|------------|
| 0.4 credits | 8,045,757 | 4.02% |
| 1 credit | 20,114,393 | 4.02% |
| 2 credits | 40,228,786 | 4.02% |
| 4 credits | 80,457,572 | 4.02% |
| 10 credits | 201,143,930 | 4.02% |
| 20 credits | 402,287,860 | 4.02% |
| 40 credits | 804,575,720 | 4.02% |
| 100 credits | 2,011,439,300 | 4.02% |
| 250 credits | 5,028,598,250 | 4.02% |
| 500 credits | 10,057,196,500 | 4.02% |
| 1,000 credits | 20,114,393,000 | 4.02% |

---

## 🛠️ Project Structure

| File | Description |
|------|-------------|
| `SHADOW_PACK.py` | Python Monte Carlo simulation engine |
| `index.html` | Playable HTML/JS game |
| `SHADOW_PACK_SDD.md` | System Design Document |
| `LICENSE` | MIT License |
| `README.md` | This file |

---

## 🚀 How to Run

### Play the Game
Open `index.html` in any modern browser — no installation required.

Enter the number of spins and select a bet. The engine will output theoretical analysis, simulation results, survival analysis, and financial breakdown.
🧠 Technical Highlights

    Multinomial distribution for exact theoretical probabilities

    Vectorized NumPy engine — up to ~800,000 spins/sec with survival mode

    500M spin verification — RTP matches theory within 1 standard error

    Professional slot metrics — RTP, hit frequency, volatility index, survival curves

    Gamble feature — 50/50 dice gamble for double-or-nothing, with number pick (×6, ×3, ×2)

    Auto-spin mode with adjustable gamble window

    Save/load/export/import via localStorage and JSON

📜 License

MIT License — see LICENSE file for details.
👤 Author

Dinko Trendafilov
GitHub: @DinkoTrendafilov

⭐ If you find this project interesting, consider giving it a star!
