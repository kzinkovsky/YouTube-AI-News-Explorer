# YouTube AI News Explorer

## Introduction

This project demonstrates the use of Generative AI to assist users in exploring current news topics by searching for relevant YouTube videos and providing informative summaries. The system leverages Gemini 2.0 Flash and controls model output through a structured prompt, enabling reliable extraction and evaluation of video content using subtitles.

### Problem Statement

> Today, it is difficult to navigate the overwhelming and often emotionally charged landscape of news — especially in video format.  
> The tone and framing of news can distort a user’s perception and influence critical decisions.

The proposed **AI News Explorer** addresses this challenge by:
- Simplifying information intake through **summarization** and **fact extraction**;
- Providing an **independent assessment** of the **emotional tone** and **agenda** of the content;
- Helping users build their own informed and balanced perspective.

### Key Features

- 🔍 Search YouTube for videos on a given news topic;
- 📝 Download subtitles and generate concise summaries in the user’s language;
- 📌 Extract verifiable facts from the subtitles;
- 🎯 Evaluate:
  - Emotional or judgmental language,
  - Presence of an agenda or strong framing,
  - Whether the video is opinion-based, analytical, or a news briefing;
- ❓ Answer user questions based only on retrieved content;
- 🌐 Multilingual support;
- ⚙️ Powered by:
  - **Gemini 2.0 Flash**,
  - **Function calling**,
  - **Structured function output (JSON)**,
  - **Prompt engineering for output control**.

### How to Run the Notebook

To run this notebook:
- Please ensure you have added your YouTube API key, Google Gemini API key, and Google Application Credentials to Kaggle Secrets under the following names:
  - YOUTUBE_API_KEY
  - GEMINI_API_KEY
  - GOOGLE_APPLICATION_CREDENTIALS_JSON  
- If you're running the notebook in a different environment (e.g. Colab, Jupyter), make sure to include code for defining the required variables with the listed API keys manually.

Try the notebook live on Kaggle → [YouTube AI News Explorer](https://www.kaggle.com/code/kirillzinkovsky/youtube-ai-news-explorer)
