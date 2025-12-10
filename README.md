# Spotify Listening History – Data Analysis & Interactive Excel Dashboard

This project explores my complete Spotify listening history, requested directly from Spotify. The goal was to create a simple, insightful, and interactive analysis that offers more flexibility and depth than Spotify Wrapped.


**Overview**

The project uses **Python (Jupyter Notebook)** and **Excel** for:

- Cleaning and merging all streaming history files  
- Converting Spotify’s JSON data into CSV  
- Creating time-based features (day names, months, AM/PM)  
- Classifying listening sessions into **daytime** and **nighttime**  
- Building a fully dynamic Excel dashboard  


**Tools & Technologies**

- **Python (Pandas)**  
- **Jupyter Notebook** – Pre-processing, JSON → CSV extraction  
- **Excel** – Further processing, pivot tables, pivot charts, slicers, and interactive dashboard visualization  


**Data Cleaning & Preprocessing**

**In Python (Jupyter Notebook)**

- Concatenated multiple streaming history datasets  
- Dropped duplicate rows  
- Removed irrelevant columns  
- Extracted JSON files into CSV format  
- Ensured uniform column structure across all files  


**In Excel**

- Converted **milliseconds → seconds**  
- Extracted time-based fields using `TEXT()`:
  - **Day name:** `=TEXT(A2, "dddd")`
  - **Month:** `=TEXT(A2, "mmmm")`
  - **AM/PM:** `=TEXT(A2, "AM/PM")`

- Classified listening time into:
  - **Daytime:** 7am–7pm  
  - **Nighttime:** 7pm–7am  

- Created pivot tables  
- Built pivot charts  
- Connected all charts to slicers  
- Designed a clean, Spotify-inspired **dark green & black** Excel dashboard  


**Visualizations Created**

- **Bar Charts:** Top artists & top songs  
- **Line Chart:** Daily listening progression  
- **Pie Chart:** Daytime vs nighttime listening  
- **Fully interactive Excel dashboard** with:
  - Year filter  
  - Month filter  
  - Dynamic listening-pattern exploration  


**Key Insights**

**1. Full Spotify listening history (2022–2025)**  
Successfully accessed and analyzed complete streaming activity since joining Spotify.

**2. Flexible, dynamic dashboard**  
Slicers allow easy filtering by year and month to explore listening habits per period.

**3. Daily listening trends**  
In 2025, Fridays had the highest listening time — a clear **TGIF effect**.

**4. Daytime vs nighttime listening**  
- Nighttime listening **peaked in 2023**  
- In 2024 and 2025, nighttime sessions reduced overall  
- But both years experienced noticeable spikes during the **ember months**  

---
