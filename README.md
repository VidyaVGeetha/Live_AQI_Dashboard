# 🌍 Live AQI Dashboard using WAQI API

This project is a real-time Air Quality Index (AQI) monitoring dashboard built with **Streamlit**. It uses the **World Air Quality Index (WAQI)** API to display live AQI, dominant pollutants, and pollutant concentration levels for any city or postcode input by the user.

> ✅ Works in **Google Colab** using **ngrok**  
> ✅ Built with **Python + Streamlit**  
> ✅ Easy to deploy or extend with maps, auto-refresh, and charts

---

## 📷 Preview

![dashboard-preview](screenshot.png)

---

## 🚀 Features

- Live AQI data from the WAQI API
- Displays AQI category (Good, Moderate, Unhealthy, etc.)
- Shows pollutant levels (PM2.5, PM10, CO, NO2, etc.)
- Simple UI with Streamlit
- Hosted via `ngrok` for public access from Colab

---

## 🧰 Tech Stack

- Python 🐍
- Streamlit 📊
- WAQI API 🌫️
- Ngrok 🌐 (for public URL in Colab)

---

## 📁 How to Use

### 🔧 Local Setup

1. Clone this repository
2. Install dependencies:

```bash
pip install streamlit requests pandas
