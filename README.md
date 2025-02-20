# 🛫 AI-Powered Travel Assistant 🚀  

An intelligent **AI Travel Assistant** built using **n8n**, integrating **Mistral AI, Google Gemini, Eleven Labs, and Pinecone** to provide seamless travel planning. This automation searches for **flights, resorts, activities, and even generates AI-powered voice responses!**  

## 📌 Features  

✅ **Webhook Integration** – Accepts user queries in real time  
✅ **Mistral AI Chat Model** – Extracts structured travel data (airport codes, dates)  
✅ **Activity & Resort Search** – Uses APIs to fetch personalized recommendations  
✅ **Flights API Integration** – Retrieves real-time flight details  
✅ **Email Agent (Google Gemini AI)** – Generates & sends travel emails  
✅ **Eleven Labs AI Voice** – Converts responses into **human-like speech**  
✅ **Automated Responses** – Sends structured trip details back to users  

---

## 🛠️ Tech Stack  

- **n8n** – Low-code automation platform  
- **Mistral AI** – Natural language processing for structured data extraction  
- **Google Gemini AI** – Advanced text generation for emails & responses  
- **Eleven Labs** – AI-powered voice synthesis  
- **Pinecone** – Vector database for efficient search and retrieval  
- **Webhooks & APIs** – Real-time request handling  

---

## 🚀 How It Works  

1️⃣ **User submits a travel request** via webhook  
2️⃣ **Mistral AI extracts travel details** (dates, locations, preferences)  
3️⃣ **Flights, Resorts & Activities APIs** fetch relevant recommendations  
4️⃣ **Google Gemini AI** drafts a personalized itinerary & email  
5️⃣ **Eleven Labs** generates a **realistic AI voice response**  
6️⃣ **Structured travel details are sent** back to the user via webhook  

---

## 📸 Screenshots  

![Workflow Screenshot](./screenshots/workflow.png)  
*(Replace this with actual screenshots of your n8n workflow)*  

---

## 🔥 Why Use n8n?  

n8n allows **seamless automation of AI-driven workflows** without complex coding. With its **low-code visual editor**, integrating **AI models, APIs, and databases** becomes effortless!  

### 🎙️ Why Eleven Labs?  
Eleven Labs enables **realistic, human-like AI-generated voices**, making AI interactions **more immersive and engaging.**  

---

## 🛠 Setup Instructions  

### 1️⃣ Prerequisites  

- **n8n account** (Sign up at [n8n.io](https://n8n.io/))  
- **API keys** for Google Gemini, Mistral AI, Pinecone, Eleven Labs  
- **Webhook URL** for receiving user queries  

### 2️⃣ Install & Run  

#### 🔹 Local Setup  
```bash
git clone https://github.com/yourusername/AI-Travel-Assistant.git
cd AI-Travel-Assistant
npm install
