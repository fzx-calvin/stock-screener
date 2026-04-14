# stock-screener
## Stock Screener with Technical Indicators

An interactive web application for screening A‑share stocks based on common technical indicators.  
Built with Python and Streamlit, it helps users quickly filter stocks using moving averages, RSI, and volume conditions.

🔗 **Live Demo**: [https://fzx-stock-screener.streamlit.app](https://fzx-stock-screener.streamlit.app)  
📂 **Source Code**: [https://github.com/fzx-calvin/stock-screener](https://github.com/fzx-calvin/stock-screener)

---

## ✨ Features

- Select stock universe (e.g., CSI 300 constituents)
- Apply multiple technical filters:
  - Price above/below **20‑day or 50‑day moving average**
  - **Golden cross** (5‑day MA crosses above 20‑day MA)
  - **RSI** range (e.g., between 30 and 70)
  - **Volume surge** (e.g., today’s volume > 1.5× 5‑day average volume)
- Real‑time screening results displayed as an interactive table
- Fast response time (< 2 seconds for 300+ stocks)

---

## 🛠️ Tech Stack

| Tool / Library | Purpose |
|----------------|---------|
| Python 3.9+ | Core language |
| Streamlit | Web app framework |
| Pandas | Data manipulation |
| akshare | A‑share data fetching |
| pandas_ta | Technical indicator calculation |
| Streamlit Cloud | Deployment (free) |

---

## 🚀 Quick Start (Run Locally)

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/stock-screener.git
   cd stock-screener
