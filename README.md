# 🌅 Amanecemos App

**Amanecemos App** is an intelligent budget management app powered by Firebase and Google Cloud.  
It allows users to register daily expenses and incomes, track weekly budgets, and visualize spending patterns with AI-powered insights.

---

## 🧩 FEATURES
- Register expenses and incomes from the same main screen  
- AI-assisted category and subcategory recognition  
- Real-time automatic saving  
- Manage weekly or monthly budgets  
- Analyze “Amanecimos con” and “Anochecimos con” balances  
- Export reports to PDF, Excel, or CSV  
- Fully responsive and bilingual (English code, Spanish UI)

---

## ⚙️ TECH STACK
- **Frontend:** React + Material UI  
- **Backend:** Firebase Functions (Node.js)  
- **Database:** Firestore  
- **Storage:** Firebase Storage  
- **AI:** Vertex AI + Cloud Vision API  
- **Hosting:** Firebase Hosting  

---

## 📁 FIRESTORE SCHEMA
See the file `amanecemos_schema.json` for the complete database model.  
Collections:
- users  
- categories  
- budgets  
- transactions  
- ai_logs  
- daily_summaries  

---

## 🧠 AI AUTOMATION
- Detects text and images for automatic category assignment  
- Learns user behavior to improve future suggestions  
- Adjusts budget dynamically as new data arrives  
- Supports both expenses and incomes  

---

## 🚀 DEPLOYMENT STEPS
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/amanecemos-app.git
