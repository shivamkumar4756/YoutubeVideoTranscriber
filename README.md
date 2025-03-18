# YouTube Video Transcriber  

# This project is a **Streamlit-based web application** that extracts transcripts from YouTube videos and generates detailed notes using **Google Gemini Pro (Gemini 1.5 Pro)**. It allows users to quickly summarize long YouTube videos into concise, easy-to-read bullet points.  

# Features  
# - Extracts transcript from YouTube videos using `youtube-transcript-api`  
# - Summarizes video content using **Google Gemini Pro (Gemini 1.5 Pro)**  
# - Displays the video thumbnail for better reference  
# - Simple and user-friendly UI with **Streamlit**  

# Tech Stack  
# - Python  
# - Streamlit  
# - Google Gemini Pro (Gemini 1.5 Pro)  
# - youtube-transcript-api  
# - dotenv  

# Project Structure  
# ```  
# ├── .env  
# ├── app.py  
# ├── requirements.txt  
# ├── README.md  
# ```  

# Environment Variables  
# Create a `.env` file in the project root and add your Google API key:  
# ```env  
# GOOGLE_API_KEY=your-google-api-key  
# ```  

# Installation  
# 1. Clone the repository:  
# ```bash  
# git clone https://github.com/shivamkumar4756/YoutubeVideoTranscriber.git  
# ```  

# 2. Navigate to the project folder:  
# ```bash  
# cd YoutubeVideoTranscriber  
# ```  

# 3. Create a virtual environment:  
# ```bash  
# python -m venv venv  
# ```  

# 4. Activate the virtual environment:  
# For Windows:  
# ```bash  
# .\venv\Scripts\activate  
# ```  
# For Linux/Mac:  
# ```bash  
# source venv/bin/activate  
# ```  

# 5. Install dependencies:  
# ```bash  
# pip install -r requirements.txt  
# ```  

# Usage  
# 1. Start the Streamlit app:  
# ```bash  
# streamlit run app.py  
# ```  

# 2. Enter the YouTube video link in the text box.  
# 3. Click **"Get Detailed Notes"** to generate the summary.  

# Requirements  
# ```  
# streamlit  
# python-dotenv  
# google-generativeai  
# youtube-transcript-api  
# ```  

# How It Works  
# 1. Extracts video ID from the provided YouTube link.  
# 2. Fetches the transcript using `youtube-transcript-api`.  
# 3. Sends the transcript to **Google Gemini Pro (Gemini 1.5 Pro)** for summarization.  
# 4. Displays the summary and video thumbnail using Streamlit.  

# To-Do  
# - [ ] Add support for multilingual transcription  
# - [ ] Improve the summarization model prompt  
# - [ ] Enhance the UI with better styling  

# License  
# This project is licensed under the **MIT License**.  

# Acknowledgements  
# - [Streamlit](https://streamlit.io)  
# - [Google Gemini Pro](https://ai.google.dev)  
# - [YouTube Transcript API](https://pypi.org/project/youtube-transcript-api)  

# **Feel free to contribute or raise an issue!** 😎  
