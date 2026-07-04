# YouTube Summarizer (AI)

### Generate YouTube video summaries using the OpenAI API (ChatGPT)

This project includes a Python script that prompts the user for a YouTube URL and leverages OpenAI's GPT-5 Nano model to generate a concise yet detailed summary of the video's content.

## Installation

### Install the dependencies

Run the following command in your terminal:

```bash
pip install openai pytube youtube-transcript-api
```

## OpenAI API Setup

1. Visit **https://platform.openai.com**.
2. Sign in or create an OpenAI account if you don't already have one.
3. Go to **API Keys**, generate a new API key, and **copy it immediately**, as it won't be displayed again.
4. Add credits to your account through the **Billing** section.
5. Create a file named `api.txt` in the project's root directory and paste **only** your API key into it. The script will automatically read this file when it starts.

> **Note:** This project only works with YouTube videos that have available captions in one of the languages specified in the `languages` parameter (line 31).
