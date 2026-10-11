# PaisaPal — Personal Finance for a ₹10,000 / 30-day challenge

A responsive React + Vite single-page finance experience built for deployment on Netlify.

## Features
- Dashboard with current balance, spending, daily allowance, month-end forecast and financial health
- Add and delete expense/income transactions
- CSV export of transactions
- Upcoming commitments and paid/unpaid toggles
- Subscription toggles and monthly subscription totals
- Savings goals with editable progress
- What-if decision simulator with projected balance, allowance, forecast and risk
- Responsive sidebar and mobile layout
- Saves data to browser `localStorage` (no server or account required)

## Run locally
1. Install Node.js (LTS).
2. Open a terminal in this folder.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL Vite prints.

## Deploy to Netlify
### Option A — Netlify UI
1. Unzip this project folder.
2. Push the folder to a GitHub repository.
3. In Netlify, choose **Add new site → Import an existing project**.
4. Connect the repository.
5. Build command: `npm run build`
6. Publish directory: `dist`
7. Select **Deploy**.

### Option B — Netlify manual deploy
Netlify's drag-and-drop deploy accepts the built site, not the raw source folder:
1. Run `npm install`
2. Run `npm run build`
3. Open Netlify's manual deploy page and drag the generated `dist` folder into it.

## Notes
- The sample data is fictional and is only there to make the dashboard feel populated.
- The day counter is set to day 11 for the demo. Change `TODAY` in `src/App.jsx` if you want another demo day.
- Browser localStorage is device/browser-specific. This prototype does not sync between devices.
- Financial health and risk scores are illustrative product-demo indicators, not professional financial advice.
- Google Fonts and chart packages need internet access when loading/installing.
