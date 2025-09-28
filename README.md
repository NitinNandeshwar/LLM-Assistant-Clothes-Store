# 🛍️ Clothing Store Chatbot  

This project implements an **AI-powered virtual shopping assistant** for a clothing store. The chatbot interacts with customers in real time, helping them find products (like t-shirts and hats), and gently encouraging them to explore ongoing sales.  

It is built using:  
- **[OpenAI API](https://platform.openai.com/)** (GPT-4o-mini model)  
- **[Gradio](https://www.gradio.app/)** for the web-based chat interface  
- **dotenv** for environment variable management  

---

## 📸 Example  

Below is a screenshot of the chatbot in action:  

![Chatbot Screenshot](3f7fcaf5-66a0-4dfa-90f6-00547447e20a.png)  

- The bot welcomes customers and asks if they are looking for something specific.  
- It promotes discounts (e.g., **50% off t-shirts, 60% off hats**).  
- If an unavailable item (like belts) is requested, the bot gracefully redirects the customer to other sale items.  

---

## ⚙️ Features  

- 💬 **Conversational Store Assistant** – Helps customers browse items.  
- 🎯 **Smart Promotions** – Actively suggests discounted products (t-shirts and hats).  
- 🚫 **Handles Unavailable Items** – If belts are requested, the bot informs users they’re not sold, and promotes alternative sale items.  
- 🌐 **Web UI with Gradio** – Simple, interactive chat interface.  
- 🔑 **Environment Key Management** – Secure API key handling with `.env`.  

---

## 🛠️ Setup  

### 1. Clone the Repository  

```bash
git clone https://github.com/yourusername/clothing-chatbot.git
cd clothing-chatbot
