# AI Chat Assistant powered by Groq

Hey there! 👋 Welcome to our AI Chat Assistant - a super friendly chat interface that brings Groq's amazing AI technology right to your fingertips. Whether you're looking for a casual chat or need some serious brainstorming, we've got you covered!

## ✨ What Makes This Special

### 🤖 Your AI, Your Way
- Pick the AI model that works best for you
- Choose how you want your AI to talk:
  - Casual Mode: Like chatting with a friend
  - Pro Mode: When you need the technical stuff
  - Creative Mode: For those out-of-the-box conversations

### 🧠 Smart Conversations
- Your AI actually remembers what you talked about
- You decide how much it should remember
- Natural flowing conversations, just like with a real person

### 💫 Clean & Simple Design
- Super easy to use interface
- Messages look neat and organized
- Quick reset when you want to start fresh
- See cool stats about your chat

### 🛡️ Rock-Solid & Secure
- Handles hiccups like a pro
- Keeps your API key safe and sound
- Runs smooth as butter

## 🚀 Let's Get Started!

### Before You Begin
You'll need:
- Python 3.10 or newer
- Conda on your machine
- A Groq API key (we'll help you set this up)

### Setting Things Up

1. **First, Grab the Code**
```bash
git clone https://github.com/aliasgar-saria/Groq-Chat-Inference-app-using-API
cd Groq-Chat-Inference-app-using-API```

2. **Create Your Space**
```bash
conda create -p envname python=3.10 -y
conda activate envname/
```

3. **Get Everything You Need**
```bash
pip install -r requirements.txt
```

4. **Quick Setup**
Just create a .env file and pop in your Groq key:
```bash
GROQ_API_KEY=your_groq_api_key
```

5. **Fire It Up!**
```bash
streamlit run app.py
```

Groq Occasionally changes the Model Names, so please do refer the supported model list here and update in app and streamlit scripts
https://console.groq.com/docs/models
