# WhatsApp Chat Analyzer

## Overview

The **WhatsApp Chat Analyzer** is a web-based tool built using **Streamlit** that allows users to upload their exported WhatsApp chat history and analyze various aspects of the conversation. The tool provides detailed insights into message activity, user interactions, word usage, sentiment analysis, and more.

## Features

- **Chat Statistics**: Displays total messages, words, media shared, and links shared.
- **Timeline Analysis**: Visualizes message activity over time (monthly and daily).
- **Activity Maps**: Shows the most active days and months for messaging.
- **Heatmap**: Provides a weekly activity heatmap based on message frequency.
- **Most Active Users**: Identifies the most active users in group chats.
- **Word Cloud**: Visualizes the most common words used in the chat.
- **Common Words**: Displays the most frequently used words, excluding stop words.
- **Emoji Analysis**: Provides statistics on the emojis used.
- **Sentiment Analysis**: Classifies messages as Positive, Negative, or Neutral, and tracks sentiment over time.

## Requirements

To run this project locally, you'll need the following libraries:

- `streamlit`
- `matplotlib`
- `seaborn`
- `pandas`
- `wordcloud`
- `emoji`
- `textblob`
- `langdetect`
- `urlextract`

You can install the required libraries using:

```bash
pip install streamlit matplotlib seaborn pandas wordcloud emoji textblob langdetect urlextract
