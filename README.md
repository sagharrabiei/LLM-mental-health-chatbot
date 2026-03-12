# Gemini Mental Health Assistant

#### Video Demo:
https://www.youtube.com/watch?v=2sE5iV2Ut8E

## Overview
The **Gemini Mental Health Assistant** is an AI-powered chatbot designed to simulate a compassionate psychology session.  
The system uses a large language model to hold supportive conversations with users and analyze uploaded text or PDF documents to detect potential emotional distress or signs of depression.

The assistant combines conversational AI with simple risk scoring to provide a final psychological summary and supportive recommendations.


## Features

- AI-powered supportive chatbot that simulates a psychologist
- Natural conversations using Google Generative AI
- Optional document analysis for deeper emotional insights
- Depression risk scoring based on emotional keywords
- Automatic psychological session summary
- Personalized mental health tips
- Simple and user-friendly web interface built with Gradio


## How It Works

### 1. Start Session
The user begins by clicking **Start Session** and entering basic information:
- Sex
- Age

### 2. Conversation
The chatbot starts a supportive dialogue with the user.  
Each message is analyzed for emotional indicators linked to depression.

### 3. Optional Document Analysis
Users can upload a **PDF or TXT file** such as:
- Personal journals
- Letters
- Written reflections

The system extracts the text and evaluates emotional signals.

### 4. Risk Scoring
Messages and uploaded documents are scanned for keywords associated with emotional distress such as:

- hopeless
- worthless
- empty
- numb
- want to die

A cumulative score determines the overall risk level.

### 5. Final Psychological Report
When the user ends the session, the system generates a full report including:

- Emotional state summary
- Depression risk rating (Low / Moderate / High)
- Mental health suggestions
- Encouragement to seek professional support if needed


## Project Architecture

Main components of the system:

1. **Conversation Engine**
   - Generates empathetic responses using the language model.

2. **Depression Scoring Module**
   - Detects emotional red flags using keyword analysis.

3. **Document Analyzer**
   - Extracts and analyzes text from uploaded PDF or TXT files.

4. **Session Logger**
   - Stores conversation history and calculates cumulative emotional risk.

5. **Final Report Generator**
   - Produces a psychological summary based on the entire interaction.

6. **Gradio Interface**
   - Provides a simple web interface for users.


#### Disclaimer

This application is intended for educational and demonstration purposes only.
It is not designed to diagnose, treat, or replace professional mental health care.