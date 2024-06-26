
# AI Bot

## Description
This is a prototype of an AI Bot, an interactive Python script that utilizes various natural language processing (NLP) techniques and external APIs to perform tasks such as defining words, finding synonyms and antonyms, fixing grammar errors, translating text, and converting text to speech. It serves as a versatile tool for language understanding and manipulation.

## Features
- Define a word and retrieve its definition from WordNet.
- Get synonyms and antonyms of a word using WordNet.
- Identify the part of speech of a word.
- Find meanings of a word based on WordNet's hypernym relations.
- Analyze English sentences and identify their parts of speech.
- Fix grammar errors in English sentences using TextBlob.
- Translate text to English or any other language using Google Translate.
- Convert text to speech with adjustable speech rate.

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

Define a word
Get synonyms
Get antonyms
Get part of speech
Find meanings
Ask an English doubt
Fix grammar
Translate text
Convert text to speech

Enter the option number: 1
Enter the word to define: computer
Definition:  an expert at calculation (or at operating calculating machines)
```

## Credits
- NLTK: Natural Language Toolkit for NLP tasks.
- TextBlob: Simplified text processing with NLP capabilities.
- Googletrans: Python wrapper for Google Translate API.
