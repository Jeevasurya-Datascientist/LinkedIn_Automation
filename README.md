# 🔗 LinkedIn Automation (No-Code Project)

Welcome to **LinkedIn Automation**, a complete plug-and-play solution to schedule and post content to LinkedIn for **200 and 400 days** — fully automated and no-code powered.

---

## 📦 What’s Included

| File | Description |
|------|-------------|
| `LinkedIn 200 Days Automation FINAL_TEMPLATE.json` | Make.com scenario blueprint for 200-day post automation |
| `LinkedIn 400 Days Automation FINAL_TEMPLATE.json` | Make.com scenario blueprint for 400-day post automation |
| `LinkedIn_Automation_Template.xlsx` | Google Sheets structure to manage your post content |

---

## 🛠 Tech Stack

- [Make.com](https://www.make.com/) – Workflow automation engine
- Google Sheets – Content database (your CMS)
- Groq API (or ChatGPT-compatible) – Post content generation
- Pexels API – Auto-fetch relevant images
- LinkedIn API – Auto-post with image + caption

---

## 🚀 Features

✅ Fully automated daily LinkedIn posts  
✅ Image + text content generated dynamically  
✅ Tracks post status, ID, timestamp in Google Sheets  
✅ Works with both 200 and 400 content rows  
✅ No coding required – just plug and run  

---

## 📂 How to Use This

### 1. Duplicate the Google Sheet Template
- File: `LinkedIn_Automation_Template.xlsx`
- Upload to your Google Drive and connect to Make.com
- Fill in `Day`, `Topic`, and `Post Content` columns

### 2. Import Blueprint to Make.com
- Open Make.com → Scenarios → Import Blueprint
- Choose either:
  - `LinkedIn 200 Days Automation FINAL_TEMPLATE.json`
  - `LinkedIn 400 Days Automation FINAL_TEMPLATE.json`

### 3. Connect Accounts
- Google Sheets
- LinkedIn
- (Optional) HTTP module for Groq API or OpenAI API
- Pexels API Key (for free stock images)

### 4. Run Scenario
- Trigger manually or schedule daily at fixed time
- Watch your posts go live every day 💥

---

## 🧠 How It Works (Overview)

1. Filters rows where post status ≠ Posted
2. Generates post caption from Topic + Prompt
3. Fetches relevant image from Pexels
4. Posts directly to LinkedIn
5. Updates Google Sheet with status + post ID

---

## 📸 Screenshots
Add carousel/visuals here showing:
- Google Sheet
- Make.com flow overview
- LinkedIn post preview

---

## 🧪 Demo + Examples
Example post content:
```
Day 1: Here's a valuable tip about life that can help you improve your mindset or skills!
```
Hashtags and structure are added automatically.

---

## 📄 License
This is a public-use template under MIT License. You may clone, fork, and use for personal/commercial use — just don’t sell as-is.

---

## 🙌 Credits
Built with 💡 by [Jeevasurya Palanisamy](https://www.linkedin.com/in/jeeva-suriya)

If you like it, give it a ⭐ or share it with a friend!

---
