# 🎯 Task 23: Automated Weather Updation Using Make

A smart automation workflow built using **Make (Integromat)** that automatically fetches real-time weather data and updates it into **Google Sheets** at scheduled intervals.

---

## 📌 Objective

- Automatically fetch current weather data for a selected city  
- Store weather details in Google Sheets  
- Schedule updates at regular intervals  
- Understand real-time API-based automation  

---

## 🧩 What to Build

Create an automation scenario where:

- Weather data is fetched using Make’s Weather module  
- Data is stored in Google Sheets  
- Scenario runs automatically based on a schedule  

---

## ⚙️ Tools Used

- 🌐 Make (Automation Platform)  
- 📊 Google Sheets  
- ☁️ Built-in Weather Module (API)

---

## 🚀 Step-by-Step Implementation

### 🔹 Step 1: Create a New Scenario
- Log in to Make  
- Click **Create a new scenario**  
- A blank canvas will appear  

---

### 🔹 Step 2: Add Weather Module
- Click the **+ icon**  
- Search: **Weather → Get Current Weather**  
- Enter the city name  
- This module provides:
  - 🌡 Temperature  
  - 💧 Humidity  
  - 🌥 Weather condition  
- Click **OK**  

---

### 🔹 Step 3: Add Google Sheets Module
- Click the **+ icon** next to Weather module  
- Select **Google Sheets → Add a Row**  
- Connect your Google account  
- Choose Spreadsheet and Worksheet  

#### 🧾 Field Mapping

| Weather Data | Google Sheets Column |
|--------------|---------------------|
| Temperature  | Temperature         |
| Humidity     | Humidity            |
| Condition    | Weather             |
| Timestamp    | Date/Time (Optional)|

---

### 🔹 Step 4: Test the Scenario
- Click **Run Once**  
- Check your Google Sheet  
- Verify that:
  - Data is inserted correctly  
  - All fields are mapped properly  

---

### 🔹 Step 5: Schedule & Activate
- Click the **clock icon**  
- Set update interval (e.g., every 1 hour)  
- Click **Activate**  

---

## 📊 Output

- Weather data is automatically updated in Google Sheets  
- Scenario runs continuously without manual intervention  

---

## ⭐ Key Features

- ✅ No coding required  
- 🌍 Real-time weather tracking  
- ⏱ Scheduled automation  
- 🔗 Easy integration with Google Sheets  
- 📈 Scalable (multiple cities supported)  

---

## 📸 Screenshots (Add for Submission)


- Make Scenario (Weather → Google Sheets)  
- Google Sheets with updated data  

```markdown
![Scenario Screenshot](./screenshots/scenario.png)
![Output Screenshot](./screenshots/output.png)
```

---

## 📁 Project Structure

```
📦 automated_weather_updation_make
 ┣ 📂 screenshots
 ┃ ┣ scenario.png
 ┃ ┗ output.png
 ┣ 📄 README.md
 ┗ 📄 Integration Weather.json 
```

---

## 🧠 Skills Acquired

- Automation using Make  
- API data handling  
- Data mapping and workflow design  
- Google Sheets integration  
- Scheduling automated workflows  

---
## 🔗 Optional Enhancements

- Add multiple cities  
- Send alerts via Email/Slack  
- Add error handling modules  

---

## 👨‍💻 Author

**Fahisa Pallikkattil**  
*- GitHub: [@https://github.com/fahisapallikkattil]
- Email: getfahisa@gmail.com*

---

## 📄 License

This project is for educational purposes.
