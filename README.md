# Deepak Finance – Modern Expense & Market Tracker

A responsive PWA for daily expense logging with live Indian market feeds, commodity prices, and an advanced SIP calculator.

## Screenshots
| Dashboard | SIP Calc | Market Strip |
|-----------|----------|--------------|
| ![dash](https://i.imgur.com/8dF1v1S.png) | ![sip](https://i.imgur.com/5oP6z8Y.png) | ![mkt](https://i.imgur.com/9qH3s8V.png) |

## Tech Stack
- **Frontend:** HTML5, Tailwind CSS (CDN), Chart.js
- **Storage:** Browser localStorage (offline-first)
- **APIs:** Finnhub (Nifty live), AMFI (NAV), MCX RSS (commodities)
- **Deploy:** Vercel (serverless, zero-cost)

## Features
1. Add / delete expenses with categories
2. Pie-chart spend breakdown
3. Live Nifty & Sensex ticker
4. SIP maturity calculator (inflation-aware)
5. PWA – install on phone / desktop
6. Dark / light mode (auto)

## Run Locally
```bash
git clone https://github.com/Deepak-Trevor/expense-mini.git
cd expense-mini
# open index.html or serve via any static server
