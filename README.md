# 💰 Income Tracker

> A sleek, real-time earnings tracker that visualizes your income as you work with multi-currency support and live exchange rates.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

### Core Features
- **Real-time Earnings Calculation** - Watch your earnings grow every second
- **Dual Calculation Modes** - Choose between hourly rate or total income for the work period
- **System Time Synchronization** - Automatically calculates earnings based on current time
- **Customizable Work Schedule** - Set your start and end times
- **Live Countdown Timer** - See remaining work time and pending earnings

### Multi-Currency Support 🌍
- **15+ Currencies** - USD, EUR, GBP, JPY, CNY, KRW, INR, AUD, CAD, CHF, HKD, SGD, MXN, BRL, RUB
- **Live Exchange Rates** - Real-time currency conversion via API
- **USD Conversion Display** - Always see your earnings in both local currency and USD
- **Automatic Rate Updates** - Exchange rates refresh every 30 minutes

### Advanced Features
- **Time Sync Mode** - When enabled, automatically calculates past earnings if you start tracking after your work begins
- **Break Mode** - Configure work/break cycles (e.g., 50 min work, 10 min break)
- **Session Summary** - Automatic summary modal when work session completes
- **Progress Tracking** - Visual progress bar for work/break cycles

### Design Features
- **Modern UI/UX** - Clean, minimalist design with glassmorphism effects
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Dark Theme** - Easy on the eyes with a sophisticated color palette
- **Smooth Animations** - Polished transitions and micro-interactions

## 🚀 Quick Start

### Option 1: Direct Open
Simply open `index.html` in your web browser.

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## 📖 Usage

### 1. Configure Work Schedule
- Enter your work **start time** (e.g., 09:00)
- Enter your work **end time** (e.g., 18:00)
- Enable **"Sync with System Time"** to auto-calculate elapsed time

### 2. Set Income Mode
Choose one of two calculation modes:

| Mode | Description |
|------|-------------|
| **Hourly Rate** | Enter your hourly wage (e.g., $50/hour) |
| **Total Income** | Enter total pay for the work period (e.g., $400/day) |

### 3. Select Currency
- Choose from 15+ global currencies
- Live exchange rates are fetched automatically
- See your earnings in both local currency and USD

### 4. Configure Breaks (Optional)
- Toggle **"Enable Break Mode"**
- Set work duration (in minutes)
- Set break duration (in minutes)
- Earnings pause during breaks

### 5. Start Tracking
- Click **"Start Tracking"**
- If time sync is enabled and current time is past start time, earnings are automatically calculated
- Watch your earnings grow in real-time!

## 💱 Supported Currencies

| Currency | Code | Symbol |
|----------|------|--------|
| US Dollar | USD | $ |
| Euro | EUR | € |
| British Pound | GBP | £ |
| Japanese Yen | JPY | ¥ |
| Chinese Yuan | CNY | ¥ |
| Korean Won | KRW | ₩ |
| Indian Rupee | INR | ₹ |
| Australian Dollar | AUD | $ |
| Canadian Dollar | CAD | $ |
| Swiss Franc | CHF | Fr |
| Hong Kong Dollar | HKD | $ |
| Singapore Dollar | SGD | $ |
| Mexican Peso | MXN | $ |
| Brazilian Real | BRL | R$ |
| Russian Ruble | RUB | ₽ |

## 🎨 Screenshots

### Main Interface
The main interface features a two-column layout:
- **Left Panel**: Work settings, income settings, and currency selection
- **Right Panel**: Real-time earnings display with USD conversion and statistics

### Status Indicators
| Status | Description |
|--------|-------------|
| 🟢 **Working** | Currently tracking earnings |
| 🔵 **Synced** | Tracking with system time synchronization |
| 🟡 **On Break** | Break period active |
| ⚪ **Idle** | Ready to start |

## 🛠️ Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables, Flexbox, Grid
- **Vanilla JavaScript** - No dependencies required
- **Exchange Rate API** - [exchangerate-api.com](https://exchangerate-api.com)

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge

### API Usage
The app uses the free tier of exchangerate-api.com for live exchange rates. If the API is unavailable, fallback rates are used.

## 📁 Project Structure

```
money_clock/
├── index.html      # Main application file
└── README.md       # Documentation
```

## 🔮 Future Enhancements

- [ ] Data persistence with LocalStorage
- [ ] Export earnings reports (CSV/PDF)
- [ ] Custom currency addition
- [ ] Sound notifications for break reminders
- [ ] Daily/weekly/monthly statistics
- [ ] PWA support for offline use
- [ ] Custom themes and color schemes
- [ ] Multiple work session tracking

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin AmazingFeature`)
5. Open a Pull Request

## 👨‍💻 Author

Made with ❤️ for productivity enthusiasts

---

<p align="center">
  <i>Track your time, maximize your earnings. 💰</i>
</p>
