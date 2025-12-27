# 📊 AI-Powered Expense Tracker  
🔗 Live App: https://your-expense-tracker.streamlit.app/

An intelligent, end-to-end **Expense Tracker application** that enables users to log, categorize, and analyze expenses through **text input, structured forms, or receipt images**, powered by **OCR and Large Language Models (LLMs)**.  
The application eliminates manual bookkeeping by automatically extracting structured expense data and presenting **real-time financial insights** through interactive visualizations.

---

## 🚀 Key Features

### 🔐 Authentication
- Secure user **signup & login**
- **User-specific data isolation** for privacy

---

### 📝 Multiple Expense Input Modes

#### ✍️ Text Input
- Natural language expense entry  
  _Example: “Paid 450 for groceries at D-Mart”_

#### 🧾 Form-Based Entry
- Structured fields for:
  - Amount
  - Category
  - Date
  - Description

#### 📸 Image Upload (Receipts / Bills)
- OCR extracts raw text from uploaded images
- LLM converts unstructured text into structured expense records

---

### 🤖 AI-Powered Expense Extraction
- **Tesseract OCR** for extracting text from receipts
- **LLM (Groq + LangChain)** parses OCR output into:
  - Amount
  - Category
  - Date
  - Description

---

### 📈 Data Visualization & Insights
- Category-wise expense breakdown
- Monthly spending trends
- Real-time chart updates after every expense entry

---

### 🗄️ Persistent Storage
- Expenses stored in **PostgreSQL (Neon Cloud)**
- Robust schema supporting:
  - Users
  - Expenses
  - Timestamps

---

## 🛠️ Tech Stack

### 🎨 Frontend
- **Streamlit** – Interactive UI and dashboards

### ⚙️ Backend / Logic
- **Python**
- **LangChain** – Prompt orchestration & LLM parsing
- **Groq LLM** – High-performance inference for expense extraction

### 🔍 OCR
- **pytesseract**
- **Pillow (PIL)** – Image preprocessing

### 🗄️ Database
- **PostgreSQL (Neon Cloud)**
- **psycopg2** – Database connectivity

### 🔒 Security
- **bcrypt** – Secure password hashing
