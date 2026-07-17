# 💼 SpareVest — Micro-Investments Made Effortless with USDT

**Save Small. Grow Big.**

SpareVest is a smart web app that empowers users to automatically invest their spare change or small amounts into crypto-backed funds using USDT (Tether). Inspired by the Jar app’s gold model, SpareVest brings the same simplicity and automation to the world of stablecoin investing.

## 🚀 What is SpareVest?

SpareVest is a micro-investment platform that:

- **Rounds up your daily purchases** and invests the spare change in USDT-backed funds.
- Enables **auto-pilot investing** with daily or weekly auto-debits as low as ₹10.
- Provides a **real-time dashboard** to track investments, USDT value, and fund growth.
- Ensures **bank-grade security** and Web3 transparency for all users.

## 🌟 Features

- **Automated Round-Ups:** Invest spare change from every transaction.
- **USDT-Based Diversification:** Access global DeFi micro-assets and crypto pools.
- **Fractional Investing:** Start with as little as ₹10.
- **Goal-Based Portfolios:** Set financial goals and track your progress.
- **Financial Education:** In-app tips and learning modules.
- **Secure & Compliant:** KYC, encryption, and regulatory adherence.
- **User-Friendly Interface:** Simple, intuitive design for all experience levels.

## ⚙️ Tech Stack

| Layer              | Technologies Used                                 |
| ------------------ | ------------------------------------------------- |
| **Frontend**       | React.js, Tailwind CSS, Axios, Chart.js           |
| **Backend**        | Node.js, Express.js, JWT                          |
| **Database**       | MongoDB (Atlas), Firebase (push notifications)    |
| **Crypto Layer**   | USDT (Tron/Polygon), Metamask Integration         |
| **Wallet Service** | Web3.js / Ethers.js, Coinbase/Trust integration   |
| **Security**       | bcrypt, OTP Auth, reCAPTCHA v3, Cloudflare        |
| **Hosting**        | Vercel (frontend), Render (backend API)           |

## 🔐 Security & Compliance

- **KYC Verification:** Aadhaar/Phone OTP for compliance
- **256-bit Encryption:** All user and wallet data
- **Multi-Factor Authentication (MFA):** On sign-in
- **Cold Wallet Options:** For large balances
- **AML & Wallet Screening:** To avoid blacklisted crypto
- **Transaction Signing & Role-Based Access Control**

> *Note: SpareVest does not hold custody of user funds. All wallet connections are secure and decentralized.*

## 💵 Revenue Model

1. **Micro Transaction Fees:** Small fee (₹0.50–₹2) per USDT transaction.
2. **Yield Sharing from Partner Pools:** Collaborate with verified DeFi protocols and share yields from pooled funds.
3. **Premium Analytics & Smart Invest Plans:** Subscriptions for curated USDT portfolios, investment bots, or auto-rebalancing.
4. **Crypto to Fiat Conversion Charges:** Small fee for INR withdrawals or UPI wallet transfers.
5. **B2B Licensing:** White-label our round-up & USDT micro-investment system for other fintechs.

## 📲 Sample User Flow

```
🛒 User buys coffee for ₹93 → App rounds up to ₹100
💰 ₹7 is auto-invested into a USDT pool (using user's linked wallet)
📈 User tracks USDT balance and fund performance in dashboard
🔁 Weekly spare-change investments continue passively
```

## 📁 Folder Structure

```
sparevest/
│
├── client/              # Frontend - React + Tailwind
│   ├── components/      # UI Widgets, Chart Visuals
│   └── pages/           # Dashboard, Wallet Connect, Settings
│
├── server/              # Node.js Backend API
│   ├── routes/          # /invest, /wallet, /kyc
│   └── services/        # Crypto integration & automation logic
│
├── scripts/             # Roundup Engine, Daily Automation
├── docs/                # API Docs, Compliance PDFs
└── README.md
```

## 📦 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-org/sparevest.git
cd sparevest

# Install dependencies
cd client && npm install
cd ../server && npm install

# Run locally
npm run dev
```

## 🎯 Roadmap

- [x] Web Wallet Integration
- [x] USDT Round-Up Engine
- [x] INR to USDT Conversion via APIs
- [ ] Launch Android/iOS App
- [ ] Smart Investment Bots
- [ ] DeFi Partnerships (Polygon, Avalanche )

## 🤝 Contributing

We welcome developers, crypto thinkers, and fintech minds to contribute!  
Check `CONTRIBUTING.md` for guidelines.

## 📫 Contact

- **Website:** www.sparevest.in
- **Email:** support@sparevest.in
- **Telegram:** @SpareVestApp
- **LinkedIn:** SpareVest Technologies

## 📃 License

MIT License © 2025 SpareVest Team

*SpareVest – Small Change, Global Impact.*
