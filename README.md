# 🌍 AI Travel Planner

Welcome to the **AI Travel Planner**! This is an intelligent travel assistant powered by **IBM WatsonX** that helps users plan their trips with ease. It only responds to **travel-related queries**. If you ask something unrelated to travel, the AI will politely decline to answer.

---

## 🚀 Features

- AI-driven travel planning
- Budget and people-based trip suggestions
- Powered by IBM WatsonX
- Friendly and simple interface

---

## 🧠 Technologies Used

- **Frontend**: React, TypeScript, TailwindCSS
- **Backend**: FastAPI
- **AI Model**: IBM WatsonX
  - watsonx.ai Runtime-aw
  - watsonx.ai Studio-kb
  - Cloud Object Storage-yj

---

## 🖼️ Project Screenshot

![AI Travel Planner Screenshot](https://github.com/Abhranil2004/AI-Travel-Planner/blob/general/screenshort/3.png)
![AI Travel Planner Screenshot](https://github.com/Abhranil2004/AI-Travel-Planner/blob/general/screenshort/2.png)
![AI Travel Planner Screenshot](https://github.com/Abhranil2004/AI-Travel-Planner/blob/general/screenshort/1.png)

---

## 🛠️ Getting Started

To run this project, you need to **start both the frontend and backend**.

---

### 🔧 Backend Setup

1. Open terminal and navigate to the backend folder:

   ```bash
   cd backend


2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the backend:

   ```bash
   uvicorn app:app --reload
   ```

> 🔐 Note: You don’t need to create a `.env` file. All required API keys and configurations are already set inside `app.py`.

---

### 🎨 Frontend Setup

1. Navigate to the frontend directory:

   ```bash
   cd frontend
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

> ⚠️ **Important:** Always run both frontend and backend together. Running only the frontend will result in errors or broken functionality.

---

## 🧪 Testing

Example input for testing:

```
Hi, plan a trip to Delhi for 7 days. My budget is ₹20000 and 2 people are coming with me.
```

Example of a blocked question:

```
Tell me about cricket.
```

Expected response: “Sorry, I can only help with travel-related queries.”

---

## 📄 License

This project is open-source and free to use under the MIT License.

---

## 👤 Developed by

**Abhranil Dutta**


