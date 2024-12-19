# Automated MOM 🚀📝

## Project Overview  
The **Automated MOM** project demonstrates the power of **Natural Language Processing** and **Large Language Models** in automating and simplifying the creation and sharing of **Minutes of Meeting (MoM)**. 🎯 This tool transforms audio or video recordings of meetings into detailed and actionable summaries, saving time and effort for organizations.  

Not only does it automate transcription, but it also provides editable MoM, giving users the flexibility to refine and finalize summaries as needed. ✨  

---

# Features 😎 
### 1.**Audio/Video Transcription 🎙️**  
- Converts recorded meeting files into accurate text conversations.  
- Supports a wide range of audio and video formats for seamless integration.  

### 2.**Meeting Summarization 📋**  
- Processes transcriptions into concise and detailed MoM.  
- Provides editable summaries for customization before sharing or archiving.  

### 3.**Streamlined MoM Management 📤**  
- Simplifies the process of generating and delegating MoM emails.  
- Reduces manual intervention, saving time and minimizing errors.  

---

# Long-Term Vision 🤘 
The project aspires to evolve into a **real-time meeting assistant** capable of:  
- Attending live meetings on behalf of the user. 🤖  
- Generating real-time transcriptions and summaries. ⏱️  
- Seamlessly integrating with organizational workflows for automated meeting management. 📊  

---

# Tech Stack 🛠️  
- **Programming Language**: 
    - **Python** 
    - **HTML, CSS, JavaScript**
- **Key Libraries/Frameworks**:  
  - **Whisper**: For high-quality transcription. 🎧  
  - **PyTorch**: Supports Whisper model implementation. 🔥
  - **Flask**: For web application development. 🌐  
  - **FFmpeg**: Enables processing of audio/video files. 🎥  
  - **NLP frameworks**: For text processing and summarization. 🧠  
- **Development Tools**: PyCharm, VS Code, GitHub for version control.  

---

# Installation Guide for Audio Transcription and MoM Summarizer 🫡

Follow these steps to set up and run the project on your local machine.

## Step-1: Prerequisites
Before starting, ensure the following are installed on your system:
1. **Python 3.11 or later**
2. **pip (Python package installer)**
3. **FFmpeg** (required for audio processing by Whisper)

---

## Step-2: How to Install FFmpeg

### Windows
1. Download and install [FFmpeg](https://ffmpeg.org/download.html).
2. Add the downloaded `ffmpeg.exe` to your PATH environment variable.

### Linux (Ubuntu/Debian)
```bash
sudo apt update
sudo apt install ffmpeg
```

### macOS
```bash
brew install ffmpeg
```


---
## Step-3: Project Setup 🛠️
1. **Fork the repository**

   You can fork it by clicking the **"Fork"** button on the top right of the page.


2. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/hpriyankaa/Automated-MoM.git 
   ```  
3. **Navigate to the Project Directory**:  
   ```bash  
   cd automated-mom  
   ```  
4. **Install Dependencies**:  
   ```bash  
   pip install -r requirements.txt  
   ```  
5. **Set Up Environment Variables**:
Create a `.env` file in the project directory and add the following:
    ```bash
    GROQ_API_KEY=your_groq_api_key
    ```
Replace `your_groq_api_key` with your actual Groq API key for quicker summarization of the transcription.

6. **Verify Installation**:
Run the following command to verify all dependencies:
    ```bash
    python -m pip list
    ```

Ensure the following packages are listed:
- `openai-whisper`
- `python-docx`
- `python-dotenv`
- `llama-index`
- `huggingface-hub`
- `nest-asyncio`
- `torch`
- `ffmpeg-python`

---
# Usage Guide 🤔  
1. **Upload** an audio or video file to the tool. 🎵  
2. The tool **transcribes** the recording into text conversations. 📄  
3. **Review and edit** the transcription (if needed). ✏️  
4. Generate a **summarized MoM** based on the transcribed text. 📋  
5. **Customize and export** the MoM in your preferred format. 💾  

---

# Future Enhancements 🤩 

- **Real-Time Transcription**: Live transcription during meetings. 🕒  
- **Cloud Integration**: Save and access transcriptions/MoM from the cloud. ☁️  
- **Multilingual Support**: Transcribe and summarize meetings in multiple languages. 🌍  
- **AI-Powered Insights**: Highlight key decisions, action items, and deadlines from conversations. 🎯  

---

# Contribution 🤝  
We welcome contributions from the community! 🧑‍💻  

To contribute:  
1. Fork the given repository. 
2. Create a new branch:  
   ```bash  
   git checkout -b feature-name  
   ```  
3. Commit your changes and push:  
   ```bash  
   git commit -m "Added feature-name"  
   git push origin feature-name  
   ```  
4. Submit a pull request. ✅  

---

# License 📜  
This project is licensed under the **MIT License**. See the `LICENSE` file for details.  

---

# Contact 📬  
For questions, feedback, or support, reach out:  

  - [Kishoreraj](https://github.com/Kishore007raj)

---
