# 🎵 Billboard Top 100 Songs Scraper 🎤  

## 📌 Project Overview  

This project is a **web scraping script** that extracts details of the **Top 100 Songs** from [Billboard](https://www.billboard.com/) using **Selenium in Python**. The script **automates navigation** through the Billboard website and scrapes key details of the songs from the **Hot 100 chart**.  

### 🚀 Features  

✅ Automatically navigates to the **Billboard Hot 100** page.  
✅ Scrapes **Song Name, Artist Name, Last Week Rank, Peak Rank, and Weeks on Board**.  
✅ Stores the extracted data in a **Pandas DataFrame** for easy manipulation.  
✅ Allows saving data as a **CSV file** for further analysis.  
✅ Uses `webdriver-manager` for **automatic ChromeDriver management**.  

---

## 📂 Data Fields Extracted  

| Field | Description |
|--------|------------|
| **🎵 Song Name** | The name of the song |
| **🎤 Artist Name** | The name of the artist |
| **📊 Last Week Rank** | The song's position in the previous week's chart |
| **🔝 Peak Rank** | The highest rank achieved by the song |
| **📅 Weeks on Board** | Number of weeks the song has stayed in the Hot 100 chart |

---

## 🛠️ Prerequisites  

Before running the script, ensure you have the following installed:  

### 📌 Required Software  

- **Python (>= 3.x)**
- **Google Chrome Browser**
- **ChromeDriver** (Automatically handled by `webdriver-manager`)  

### 📌 Install Required Libraries  

Run the following command to install dependencies:  

```bash
pip install selenium pandas webdriver-manager
