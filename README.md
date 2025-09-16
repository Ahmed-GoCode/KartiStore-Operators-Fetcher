# 📡 KartiStore Operators Fetcher

This Python script allows you to fetch **mobile operators** from the [KartiStore API](https://www.kartistore.com) using a specific **country code**.  
It uses the `requests` library to send a request and prints the API response in a **formatted JSON** output.

---

## 🚀 Features
- Fetch operators list for any country by setting its code.
- Outputs results in clean **pretty-printed JSON**.
- Handles invalid JSON responses safely.

---

## 📂 Installation
Make sure you have **Python 3** installed. Then install dependencies:

```bash
pip install requests
```

---

⚡ Usage

Run the script with: 
```bash
python main.py

```
By default, the script fetches operators for country code 961 (lebanon).
You can change the country code inside the script:
---


---
params = {
    'countryCode': "961"  # Replace with your country code
}

---
