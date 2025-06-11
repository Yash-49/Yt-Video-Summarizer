# 🎬 YouTube Video Summarizer (Streamlit + Gemini API)

An interactive Streamlit app that extracts and summarizes transcripts from YouTube videos using Google's Gemini API.

---

## 🚀 Features

- 🔗 Accepts any public YouTube video URL
- 📜 Automatically fetches the transcript (if available)
- 🧠 Summarizes the content using Gemini Pro (via Google Generative AI API)
- 💻 User-friendly web interface built with Streamlit

---

## 🛠️ Tech Stack

- Python
- Streamlit
- `youtube-transcript-api`
- `google-generativeai` (Gemini API)
- `python-dotenv` (for secure API key handling)

---

## 📥 Setup Instructions
  Step 1: Clone the Repository

    git clone https://github.com/your-username/yt-video-summarizer.git
    cd yt-video-summarizer

  Step 2: Create and Activate Virtual Environment

    # Linux / macOS
    python3 -m venv venv
    source venv/bin/activate

    # Windows
    python -m venv venv
    venv\Scripts\activate

  Step 3: Install Required Packages

    pip install -r requirements.txt

  Step 4: Get Your Gemini API Key
  
    Go to https://makersuite.google.com/app

  Log in with your Google account
  Navigate to API Access and generate your API Key
  Copy the key (keep it secure!)

  Step 5: Store Your API Key Securely
  
Create a file named .env in the project root directory and add:

          GEMINI_API_KEY=your_actual_api_key_here
Note: Don’t share this .env file or upload it to GitHub. It contains your private key.

Step 6: Run the Streamlit App

    streamlit run app.py
