# 🚀 Vloxiblox AI - Quick Start Guide

## What You Have Now:
A simple chatbot that talks to Google's Gemini AI and remembers your conversations!

## How to Run It:

### On Your Computer:
1. **Download Python** from [python.org](https://www.python.org) (if you don't have it)
2. **Download your code:**
   - Go to your repo
   - Click the green "Code" button
   - Click "Download ZIP"
   - Extract the folder

3. **Open Terminal/Command Prompt** in that folder
4. **Run these commands:**
   ```
   pip install -r requirements.txt
   python main.py
   ```

### On Your Android Phone:
Use **Termux** (free app from Play Store):
1. Install Termux from Google Play Store
2. Open Termux and run:
   ```
   pkg update
   pkg install python
   git clone https://github.com/YOUR_USERNAME/vloxiblox-ai
   cd vloxiblox-ai
   pip install -r requirements.txt
   python main.py
   ```

## Setup Your API Key:

1. Open `main.py` in GitHub's web editor
2. Find this line: `API_KEY = "YOUR_GEMINI_API_KEY_HERE"`
3. Replace it with your actual Gemini API key
4. Example: `API_KEY = "AIzaSyD1234567890..."`
5. Click "Commit changes"

## Try These Commands:

```
🧑 You: Hello!
🤖 Vloxiblox: [responds intelligently]

🧑 You: save
✅ Memory saved to memory.json

🧑 You: quit
👋 Goodbye!
```

## Next Steps (Coming Soon):
- ✅ Chat (Done!)
- 📚 Homework Help (Add system prompts)
- 💾 Memory (Done!)
- 🎤 Voice (Need speech-to-text)
- 🌐 Web Search (Need search API)

## Having Issues?
1. **API Key not working?** → Double-check you copied it correctly
2. **ModuleNotFoundError?** → Run `pip install -r requirements.txt` again
3. **Still stuck?** → Create an issue in your GitHub repo

Happy chatting! 🎉
