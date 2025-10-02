# React Crypto Portfolio

## Project Goal
This is a learning project created to practice React by building a cryptocurrency portfolio application.  
The app allows users to enter how much cryptocurrency they own, and it calculates and displays the total portfolio value.

## Tech Stack
- **React 18** – UI library
- **Vite 5** – build tool for fast development
- **Ant Design (antd)** – UI components
- **React Chart.js 2** – charts and visualizations
- **ESLint** – code linting
- **JavaScript / JSX**

## How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/NikitaSipeykin/react-crypto-initial.git
   cd react-crypto-initial
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Start the development server  
   ```bash
   npm run dev
   ```

4. Open the app in your browser at the URL shown in the terminal (usually http://localhost:5173).

_No deployment planned, local development only._

## Data Structure (API Simulation)
Since the project does not have a backend, data is static and stored locally.  
The structure of the portfolio data looks like this:

```js
export const cryptoData = {
  result: [
    {
      id: 'bitcoin',
      icon: 'https://static.coinstats.app/coins/1650455588819.png',
      name: 'Bitcoin',
      symbol: 'BTC',
      rank: 1,
      price: 44870.39834657236,
      priceBtc: 1,
      volume: 35728788775.15447,
      marketCap: 879141227764.5575,
      availableSupply: 19592900,
      totalSupply: 21000000,
      priceChange1h: -0.34,
      priceChange1d: 0.94,
      priceChange1w: 5.02,
      redditUrl: 'https://www.reddit.com/r/Bitcoin/',
      websiteUrl: 'http://www.bitcoin.org',
      twitterUrl: 'https://twitter.com/bitcoin',
      explorers: [
        'https://blockchair.com/bitcoin/',
        'https://btc.com/',
        'https://btc.tokenview.io/',
        'https://www.oklink.com/btc',
        'https://3xpl.com/bitcoin',
        'https://blockchain.coinmarketcap.com/chain/bitcoin',
        'https://blockexplorer.one/btc/mainnet',
      ],
    },
  ]
}
  
```

This JSON is used to simulate portfolio balance and value calculations.

## Features
- Add and track different cryptocurrencies manually
- Display portfolio total value
- Show visual charts of holdings distribution using Chart.js
- Simple and clean UI with Ant Design
