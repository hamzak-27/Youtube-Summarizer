# Youtube-Summarizer

This project provides an end-to-end solution to download YouTube videos, transcribe them using OpenAI's Whisper model, and summarize the transcriptions using LangChain with OpenAI's GPT-4 model. Additionally, the project allows for vector storage and retrieval of text summaries, enabling efficient question-answering based on video content.

## Features

- **Video Download**: Automatically downloads YouTube videos in the best available quality.
- **Transcription**: Converts the video to text using the Whisper model.
- **Summarization**: Summarizes the transcribed text into a concise format, with options for map-reduce, bullet points, and refinement-based summarization.
- **Vector Storage**: Stores the text embeddings using DeepLake and enables retrieval for question-answering.
- **Question-Answering**: Answers questions based on the content of the transcribed video.
