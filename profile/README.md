# Vite une place

**Vite une place** is a web platform that helps drivers find available parking spots in real time.  
The goal is to make parking easier and faster by showing live availability directly on the map.

## 🌍 Available cities
- **Orléans**
- **Aix-en-Provence**
- **Marseille**

Our long-term objective is to expand coverage to all major cities in France.

---

## ⚙️ Tech Stack

### Website
- **Backend:** Python API / PHP (for crons)
- **Database:** MySQL
- **Frontend:** Next.JS 15 / React / TailwindCSS

### Data Fetching
- A cron job runs every 15 minutes to fetch parking availability from multiples data sources
- Implemented in **PHP 8.2** and directly linked to the main API.  

### API
- Custom API
- Powered by **Python (Django)** & **MySQL**

---

## 🚗 How it works
1. Data is collected from multiples data sources.
2. Our system processes this data every 15 minutes.
3. Availability information is served through our API.
4. The website displays live parking availability on an interactive map.  

---

## 🔮 Roadmap
- Extend coverage to more cities in France.  
- Improve accuracy and refresh rates of parking availability.  
- Enhance the website’s user experience and performance.
- Open our API to external users.

---

## 📫 Contact
For more information, visit: **[viteuneplace.fr](https://viteuneplace.fr)**  
