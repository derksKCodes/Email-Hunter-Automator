# 📧 Email Hunter Automator

A **full-stack Email Extractor** that automates **extracting emails from websites listed in your Excel files**. Upload an Excel file, process it through a clean web interface, and download an updated file with extracted emails filled automatically.  Uses Python (Selenium + BeautifulSoup) for backend scraping and a React + Tailwind frontend for a clean upload/download interface. Ideal for lead generation, outreach, and automated contact list building.

---

## ✨ Key Features

✅ Upload Excel files for email extraction (Column K: websites → Column J: extracted emails)  
✅ Crawls **Contact, About, and Privacy pages** automatically  
✅ Extracts emails from **social media profiles** using Selenium  
✅ Supports **JavaScript-rendered websites** via headless Chrome  
✅ Multi-threaded processing for speed  
✅ Download processed Excel files directly  
✅ Clean, modern **frontend interface** for ease of use  
✅ **Deduplication** and accurate regex filtering  
✅ Ready for deployment or internal workflow automation

---

## 🛠️ Tech Stack

### **Frontend**
- **React + TypeScript**
- **Tailwind CSS** for styling
- **Vite** for fast builds

### **Backend**
- **Python 3.8+**
- `pandas`, `requests`, `BeautifulSoup`, `selenium`, `openpyxl`
- `concurrent.futures` for multi-threading
- REST API for processing Excel uploads

---

## 🚀 Live Demo

![UI Screenshot](./public/placeholder.png)

---

## 📦 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/derksKCodes/email-extractor.git
cd email-extractor
