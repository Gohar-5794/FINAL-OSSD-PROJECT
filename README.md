# FINAL-OSSD-PROJECT
# 🌦️ Tkinter Weather App

This is a simple GUI-based Weather App built using **Python Tkinter** and the **OpenWeatherMap API**.  
It allows users to enter a city name and get real-time weather data. The app also includes a history window and an about screen — fulfilling the requirement of at least 3 modules.

---



## ✅ Features

- GUI created with Tkinter
- Real-time weather data using OpenWeatherMap
- Search history (saved locally)
- About screen with app details
- Clean layout using `pack()` method
- Multiple windows (3 modules/screens)

---


//THIS IS THE SYNTAX FOR TKINTER to set geomerty
/*
    root = tk.Tk()
    root.title("My Tkinter App") # Optional: Set window title
    root.geometry("400x300") # Optional: Set window dimensions
*/

## 🛠️ Technology Stack

- Python 3.13+
- Tkinter (built-in with Python)
- `requests` library (for HTTP requests)
- OpenWeatherMap API
- Git & GitHub

---

## 🚀 How to Run the App

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

> Replace the link with your actual GitHub repository link.

---

### 2. Install dependencies
```bash
pip install requests
```

> `tkinter` is already included with Python — no need to install it.

---

### 3. Set your API key

Create a file named `config.py` and paste this line:

```python
API_KEY = "your_openweathermap_api_key"
```

If you already have `config.py`, just replace the key inside it.

---

### 4. Run the app
```bash
python main.py
```

A GUI window will open. Type a city name (e.g., *Lahore*) and click **Get Weather**.

---

## 📂 Project Structure

```
├── main.py           # Main GUI logic
├── weather_api.py    # Fetches weather data from API
├── config.py         # Stores your API key
├── history.txt       # Saves previous weather searches
└── README.md         # Project documentation (this file)
```

---

## 🙋 Team Members

- Ashir Ahmad (Group Lead)
- Obaid
- Zulfqar

---



## 📝 License

This project is developed as part of the university OSSD course for educational purposes only.

