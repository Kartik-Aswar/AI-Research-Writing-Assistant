
# AI-Research-Writing-Assistant

A powerful content generation system built with **CrewAI** that combines intelligent research, advanced language models like **gemini-2.0-flash**, and Serper-powered search to generate high-quality blog posts on any topic.

![Screenshot 2025-04-16 003608](https://github.com/user-attachments/assets/f9446042-9836-49b7-b947-ff6673bcc2fb)

*Web interface preview*

## 🚀 Features

- 🔍 Automated research using **Serper API** and **Google Gemini**
- ✍️ AI-powered writing via **CrewAI framework**
- 📊 Sentiment analysis and keyword extraction
- 🖥️ Interactive **Streamlit** web interface
- 📥 Downloadable **Markdown** output for easy publishing

## 📋 Prerequisites

- Python 3.9+
- API keys for:
  - Google Gemini
  - Serper API

## 🛠️ Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd AI-Research-Writing-Assistant
```

2. Create and activate a virtual environment:
```bash
conda create -n crewai python==3.12 -y
conda activate crewai
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Add your API keys:
```env
GEMINI_API_KEY=your_google_gemini_key
SERPER_API_KEY=your_serper_key
```

## 🚀 Running the Application

### Command Line Version
```bash
python app.py
```

### Streamlit Web Interface
```bash
streamlit run streamlit_app.py
```
Then go to [http://localhost:8501](http://localhost:8501)

## 💻 Usage

### Web Interface:
1. Enter your desired topic in the sidebar
2. Adjust temperature (creativity level)
3. Click **Generate Content**
4. View AI-generated blog post
5. Download as `.md` (Markdown file)

![Markdown Output Preview](./assets/download_preview.png)
*Markdown download preview*

### Command Line:
1. Edit the topic inside `app.py`
2. Run the script
3. Results will print to console

## 🗂️ Project Structure

```
AI-Research-Writing-Assistant/
├── streamlit_app.py     # Streamlit interface
├── app.py               # CLI version
├── requirements.txt     # Dependencies
├── .env.example         # Sample environment vars
├── README.md            # Documentation
└── assets/              # App screenshots and preview images
    ├── app_interface.png
    └── download_preview.md
```
