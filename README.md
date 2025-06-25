# 🎤 Lyrics to PowerPoint Generator

This Streamlit app allows you to paste song lyrics (e.g. copied from Genius.com) and automatically generates a PowerPoint presentation. Each slide contains 4 lines of lyrics, and all section headers like `[Verse 1]`, `[Chorus]`, and promotional content are removed.

## ✨ Features

- Cleans lyrics from Genius.com (removes [Verse], [Chorus], etc.)
- Removes promotional content and suggestions
- Splits lyrics into slides with 4 lines each
- Generates a downloadable `.pptx` presentation

## 🚀 How to Use

### 🔗 Online (Streamlit Cloud)

1. Fork this repository to your GitHub account.
2. Go to streamlit.io/cloud and sign in.
3. Click **“New app”**, select your repository and `app.py` as the main file.
4. Click **Deploy** and enjoy!

### 🖥️ Run Locally

```bash
git clone https://github.com/your-username/lyrics-to-ppt.git
cd lyrics-to-ppt
pip install -r requirements.txt
streamlit run app.py
