# 🎥 Cinema Ticket Sales Forecasting with LSTM

This repository contains a complete pipeline for forecasting cinema ticket sales using a Long Short-Term Memory (LSTM) neural network. The project uses historical daily ticket sales data to predict future values, providing insights for operational planning and marketing optimization.

---

## 📊 Dataset

The dataset includes:
- Daily ticket sales per film and cinema
- Show time, ticket price, capacity, occupancy, and date features

**Sample Features:**
- `film_code`
- `cinema_code`
- `tickets_sold`
- `ticket_price`
- `occu_perc`
- `capacity`
- `date` (used for time series)

---

## 🧠 Model

Different models comparison , Feature Extraction from auto encoders , CNN and then LSTM. ALso implemented a 16 patch Transformer architecture.

### 🔧 Features
- Multivariate LSTM support
- Data preprocessing and scaling
- Sequence generation for time series
- Train/test split
- Forecasting for next N days
- Visualization of results

---

## 🛠️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/itsAbhayRaj/RUL_DL.git
cd cinema-ticket-forecasting
