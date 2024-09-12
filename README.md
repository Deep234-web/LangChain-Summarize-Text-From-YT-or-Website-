# LangChain: Summarize Text From YouTube or Website

This project uses LangChain and Groq's Gemma-7b-It model to summarize content from YouTube videos or websites. The app allows users to input a URL and receive a summarized version of the content in 300 words.

## Features
- Summarizes content from both YouTube videos and websites.
- Uses Groq's LLM (Gemma-7b-It) to generate concise summaries.
- Interactive Streamlit interface with easy-to-use inputs.
- Supports both YouTube URLs and general website URLs.

## Usage
- Open the live app in your browser [at http://localhost:8501.](https://gwoqrmpxm5pm6rzadwpszi.streamlit.app/)
- Enter your Groq API key in the sidebar to enable summarization features.
- Paste either a YouTube video URL or a website URL in the main text input field.
- Click the "Summarize the Content from YT or Website" button to generate a summary.
- The summarized output will be displayed on the screen.

## Requirements
- Python 3.7+
- Groq API key
- Streamlit
-nLangChain
- YouTubeLoader and UnstructuredURLLoader from langchain_community

## Dependencies
- validators: Used to validate URLs.
- ChatGroq: For generating the summary using the Groq API.
- YoutubeLoader: For extracting content from YouTube videos.
- UnstructuredURLLoader: For extracting content from websites.

## API Key
- You will need a Groq API key to run the summarization feature. Enter the key in the sidebar to authenticate and begin generating summaries.
