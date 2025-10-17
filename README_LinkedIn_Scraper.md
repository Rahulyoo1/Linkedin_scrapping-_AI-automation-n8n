# 🚀 LinkedIn Post Scraper Automation using n8n

This project is an **AI-powered LinkedIn Post Scraper Automation** built with **n8n**, designed to automatically collect and organize post details from LinkedIn profiles.  
It uses **Google Sheets** integration, **API connectors**, and intelligent filtering to deliver clean and actionable data.

---

## 🧩 Workflow Overview

### 🔹 Step 1: Manual Trigger
The workflow starts manually — this allows you to control when the automation runs and ensures you can choose specific profiles or datasets before execution.

### 🔹 Step 2: Get Profile Details from Google Sheet
The workflow fetches LinkedIn profile URLs or user identifiers from a **Google Sheet**.  
Each row typically contains the profile link or username of the person or page whose posts you want to analyze.

### 🔹 Step 3: Connect to API for Data Extraction
It then calls the **LinkedIn API / custom scraping API** to fetch post-related data such as:
- Post text/content  
- Likes  
- Comments  
- Shares  
- Posting date  
- Engagement metrics  

### 🔹 Step 4: AI-Based Data Filtering
After fetching, the data passes through a **filtering logic** (customized based on your criteria).  
This helps you extract only the relevant details — for example:
- Only posts from the last 30 days  
- Posts with more than 50 likes  
- Specific hashtags or keywords  

### 🔹 Step 5: Append Results into New Google Sheet
Finally, the cleaned and structured data is appended into a **new Google Sheet**.  
This ensures the output is easy to analyze and visualize later in tools like Power BI or Excel.

---

## ⚙️ Tech Stack

- **n8n** (Workflow automation platform)  
- **Google Sheets** integration  
- **LinkedIn Data API / Scraper API**  
- **AI Filter & Data Processing Node**

---

## 🧠 Key Features

✅ Fully automated LinkedIn post scraping  
✅ Customizable API integration  
✅ Dynamic filtering based on keywords or engagement  
✅ Automatic Google Sheets data update  
✅ Scalable — works for multiple profiles at once  

---

## 🚀 How to Use

1. Import the workflow JSON file into **n8n**.  
2. Configure:
   - Google Sheets credentials  
   - API key / endpoint for LinkedIn data  
3. Enter your LinkedIn profile links in the input sheet.  
4. Manually trigger the workflow from n8n UI.  
5. View the structured data in the output Google Sheet.  

---

## 📊 Example Output

| Profile | Post Text | Likes | Comments | Posted On | Hashtags |
|----------|------------|--------|-----------|------------|-----------|
| John Doe | "AI automation is the future..." | 128 | 12 | 2025-10-10 | #AI #Automation |
| Jane Smith | "Exploring new ways to use data..." | 75 | 9 | 2025-10-09 | #DataScience |

---

## 🧾 License

This project is open-source and available under the **MIT License**.


## 🙌 Author

**Rahul Yadav**  
💼 Data Science & AI Automation Enthusiast  
🔗 [LinkedIn Profile] www.linkedin.com/in/rahul-yadav-57b813257  

---

## 🌟 Showcase

This automation demonstrates the power of **Automation** in social media analytics — transforming manual LinkedIn tracking into an intelligent, scalable, and time-saving solution.
