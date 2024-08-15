# Sarvam_ShukaV1_Demo

## Introduction
This is a demo for Sarvam's Shuka V1 model, a state-of-the-art language model that natively understands audio in Indic languages. For more details, see the [Model Card](https://huggingface.co/sarvamai/shuka_v1).

## About Shuka V1
Shuka V1 is an encoder-decoder model built by combining:
- Saaras v1: A state-of-the-art, in-house audio encoder
- Meta's Llama3-8B-Instruct as the decoder

Key features:
- Understands multiple Indic languages
- Trained on less than 100 hours of audio
- Performs well on zero-shot QA in various Indic languages

## How to Use This Demo

1. Open the provided Google Colab notebook.
2. Run the installation cell to set up the required libraries.
3. Upload an audio file (mp3, m4a, or mp4) when prompted.
4. The model will process the audio and provide a response.
5. Review the output to see how Shuka V1 interpreted your audio input.

## Supported Languages
While trained primarily on English and Hindi, Shuka V1 has shown good performance on:
Bengali, English, Gujarati, Hindi, Kannada, Malayalam, Marathi, Oriya, Punjabi, Tamil, and Telugu.

## Tips for Best Results
- Use clear audio recordings
- Try different Indic languages to test the model's multilingual capabilities
- Experiment with various types of queries or statements in your audio

## Feedback
 Please report any issues or share your experience in the repository's Issues section.

Enjoy exploring the capabilities of Shuka V1!
