# ================================================
#        💱 Currency Converter - Python 🐍
# ================================================

# 📄 Description:
# A simple Python script that converts currency using real-time
# exchange rates via ExchangeRate-API.

# 🔧 Requirements:
# - Python 3.6+
# - requests module (install via pip)

# 🗂️ Files:
# ├── converter.py        # Main script
# └── API.py              # (Optional) Contains your API_KEY

# 🔑 Setup:

# 1. Clone the repo:
git clone https://github.com/yourusername/currency-converter-python.git
cd currency-converter-python

# 2. Install dependencies:
pip install requests

# 3. Add your ExchangeRate-API key:
#    Option A: Edit converter.py and set your API_KEY directly.
#    Option B: Create a separate file API.py:
echo 'API_KEY = "your_actual_api_key"' > API.py

# ▶️ Run the script:
python converter.py

# 💡 Sample Usage:
# -------------------------
# Enter the FROM currency (e.g. USD): USD
# Enter the TO currency (e.g. EUR): EUR
# Enter the amount: 100
# => 100 USD = 91.35 EUR
# -------------------------

# 🧠 Tips:
# - Make sure your currency codes are valid ISO codes (like USD, EUR, PKR).
# - Check your API key limits (free tier allows 1,500/month).

# 🌐 API Used:
# https://www.exchangerate-api.com/

