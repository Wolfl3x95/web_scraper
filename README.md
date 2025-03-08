# Web Scraper by W3X - Raffaele Brancaccio 🚀

📡 **A powerful Python web scraper** that extracts product titles and prices from any website.

![GitHub License](https://img.shields.io/badge/License-MIT-yellow.svg)  
![GitHub Repo Size](https://img.shields.io/github/repo-size/Wolfl3x95/web_scraper)  
![GitHub Last Commit](https://img.shields.io/github/last-commit/Wolfl3x95/web_scraper)  

---

## 📜 **Features**
✅ **Extracts product titles and prices automatically**  
✅ **Saves data in CSV, PDF, or Excel**  
✅ **Bypasses website restrictions with user-agent simulation**  
✅ **Ensures W3X credits remain in all generated files**  
✅ **Lightweight and easy to use**  

---

## 🛠 **Installation**
First, install the required dependencies:
```bash
pip install requests beautifulsoup4 pandas fpdf openpyxl
```


---

If the website has **Cloudflare protection**, install:
```bash
pip install cloudscraper
```

---

If the website uses **JavaScript to load data**, install:
```bash
pip install selenium webdriver-manager
```
---

##🚀 Usage
Run the script and enter the website URL:
```bash
python web_scraper.py
```
Then, choose the output format:
📄 CSV | 📝 PDF | 📊 Excel

---

##⚙ How It Works
1️⃣ The script sends an HTTP request to the given URL.
2️⃣ It parses the HTML to extract product titles and prices.
3️⃣ It saves the data in the selected format (CSV, PDF, or Excel).
4️⃣ It ensures W3X credits remain in all generated files to protect the author’s work.

---

##🏆 Example Output
Here is an example of product extraction:
```bash
Inserisci l'URL del sito da cui estrarre i dati: https://esempio.com/prodotti
In quale formato vuoi salvare i dati? (csv/pdf/excel): pdf
Dati salvati con successo in prodotti_estratti.pdf
```
📸 Example of Extracted PDF

📌 Title: USB-C Charger 20W
💰 Price: €19.99

📌 Title: Bluetooth Noise Cancelling Headphones
💰 Price: €49.99

---

##📞 Contact
🔹 Created by W3X - Raffaele Brancaccio
🔹 LinkedIn: Raffaele Brancaccio
🔹 GitHub: Wolfl3x95
🔹 Email: dev.raffaelebrancaccio@gmail.com

Need custom scripts or modifications? Feel free to reach out! 🚀

---

##📜 License
This project is licensed under the MIT License.
You are free to modify and distribute it, but you must keep the original W3X credits visible in all generated files.

---

##⭐ Support & Contributions
🔹 Give a ⭐ on GitHub if you find this useful!
🔹 Feel free to submit issues or open pull requests for improvements.
