# 🌍 story-transformer

## 🚀 Project Overview
This project **fetches**, **summarizes**, **translates**, and **simplifies** environmental articles using **Azure OpenAI & Microsoft Translator**.

## 📌 Features
✅ Fetch articles from WordPress (GraphQL API)  
✅ Simplify and summarize articles with GPT-4  
✅ Translate articles into multiple languages  
✅ Serve processed content via an API  

---

## 🛠️ **Setup Instructions**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/story-transformer.git
cd story-transformer
```

### **2️⃣ Pull the Latest Changes**
Before making any modifications, always pull the latest changes from GitHub:
```bash
git pull origin main
```
✅ This ensures your local copy is up to date with the latest version.

### **3️⃣ Create & Activate a Virtual Environment**
Each time you start working on the project, you need to activate the virtual environment.

#### **Windows (Git Bash)**
```bash
python -m venv venv
source venv/Scripts/activate
```

#### **Windows (Command Prompt)**
```bash
python -m venv venv
venv\Scripts\activate
```

#### **Mac/Linux**
```bash
python3 -m venv venv
source venv/bin/activate
```

✅ **You must activate the environment every time you start working on the project.**

### **4️⃣ Install Dependencies**
After activating the virtual environment, install the necessary dependencies:
```bash
pip install -r requirements.txt
```

### **5️⃣ Run the Streamlit App**
#### **For Mac OS and Windows**
```bash
# (1) Move into the api folder
cd api

# (2) Run the Streamlit app
streamlit run app.py
```
Visit: `http://localhost:8501` to view processed articles.

---

## 🤝 **How to Contribute**
1. **Pull the latest changes** before working:
   ```bash
   git pull origin main
   ```
2. **Activate the virtual environment**:
   - **Windows (Git Bash)**:
     ```bash
     source venv/Scripts/activate
     ```
   - **Windows (Command Prompt)**:
     ```bash
     venv\Scripts\activate
     ```
   - **Mac/Linux**:
     ```bash
     source venv/bin/activate
     ```
3. **Make edits or add new scripts** in the `scripts/` folder.
4. **Commit and push your changes**:
   ```bash
   git add .
   git commit -m "Added new article processing feature"
   git push origin main
   ```

---
