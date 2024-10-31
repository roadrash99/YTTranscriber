

# YouTube Video Transcriber & Summarizer

This AI-powered web application uses Google Generative AI and Streamlit to transcribe and summarize YouTube videos, enabling users to quickly understand video content without watching the entire video. By extracting accurate transcripts and generating concise summaries, this tool is ideal for users who want to capture the essence of video content efficiently.

## Features

- **Transcription**: Leverages the `youtube-transcript-api` to extract accurate transcripts directly from YouTube videos.
- **Summarization**: Uses Google Generative AI to provide concise summaries, helping users quickly grasp the main points of the video.
- **User-Friendly Interface**: Built with Streamlit, the interface is clean and easy to navigate, making it simple for anyone to transcribe and summarize YouTube content.
- **Secure API Management**: Python Dotenv is used to securely manage API keys, ensuring a safe and seamless user experience.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/roadrash99/YTTranscriber.git
    cd YouTube-Transcriber-Summarizer
    ```

2. **Install Required Packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure Environment Variables**:
    - Create a `.env` file in the root directory.
    - Add your API keys as follows:
      ```plaintext
      GOOGLE_API_KEY=your_google_api_key
      YOUTUBE_API_KEY=your_youtube_api_key
      ```

## Usage

1. **Run the Application**:
    ```bash
    streamlit run app.py
    ```

2. **Input Video URL**:
   - Enter the YouTube video URL to extract the transcript and summarize the content.

3. **View Results**:
   - The application will display the full transcript and a concise summary of the video content.

## Tech Stack

- **Backend**: Python
- **Frontend**: Streamlit
- **APIs**: Google Generative AI, youtube-transcript-api
- **Security**: Python Dotenv for API key management
