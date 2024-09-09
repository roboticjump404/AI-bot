
# AI Bot

## Description
This prototype AI Bot is an interactive Python script designed to leverage natural language processing (NLP) techniques and external APIs to enhance language understanding and manipulation. It offers a range of functionalities to assist with language tasks, including word definitions, synonyms and antonyms, grammar correction, text translation, and speech synthesis. This versatile tool aims to provide comprehensive support for various language processing needs.

## Features
- **Define a Word**: Retrieve definitions from WordNet to understand the meaning of any word.
- **Get Synonyms**: Find synonyms of a word using WordNet to expand vocabulary.
- **Get Antonyms**: Identify antonyms of a word to understand its opposite meanings.
- **Get Part of Speech**: Determine the grammatical category of a word (e.g., noun, verb, adjective).
- **Find Meanings**: Explore the meanings of a word based on its hypernyms (general terms).
- **Ask an English Doubt**: Analyze and identify parts of speech in English sentences to clarify grammatical doubts.
- **Fix Grammar**: Correct grammatical errors in sentences using TextBlob for improved clarity.
- **Translate Text**: Translate text into English or other languages using Google Translate.
- **Convert Text to Speech**: Convert text into spoken words with adjustable speech rate using text-to-speech synthesis.

## Options
1. **Define a word**: Enter a word to retrieve its definition.
2. **Get synonyms**: Enter a word to find its synonyms.
3. **Get antonyms**: Enter a word to find its antonyms.
4. **Get part of speech**: Enter a word to determine its part of speech.
5. **Find meanings**: Enter a word to explore its meanings.
6. **Ask an English doubt**: Enter an English sentence to analyze its parts of speech.
7. **Fix grammar**: Enter a sentence to correct its grammar.
8. **Translate text**: Enter text to translate it to English or specify the source language.
9. **Convert text to speech**: Enter text to convert it to speech with adjustable rate.

## Example
```
$ python ai_bot.py

Hello! This is an AI bot. How can I assist you today?

1. Define a word
2. Get synonyms
3. Get antonyms
4. Get part of speech
5. Find meanings
6. Ask an English doubt
7. Fix grammar
8. Translate text
9. Convert text to speech

Enter the option number: 8
Enter the text to translate to English: मैं अच्छी तरह से हिंदी नहीं बोलता
Translated text: I don't speak Hindi well
```

## Credits
- **NLTK**: Natural Language Toolkit for performing various NLP tasks.
- **TextBlob**: Simplified text processing library for grammatical correction and sentiment analysis.
- **Googletrans**: Python wrapper for Google Translate API for text translation.
- **Pyttsx3**: Text-to-speech conversion library for generating spoken text.

---
