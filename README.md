# Agent-AURA
Agent AURA - AI for Understanding, Reference &amp; Action. A personalized AI assistant for Tata Steel that automatically generates AI learning content, posters, and engagement questions.

## Problem

Currently AURA content creation is manual.

Team members:
- Select topic
- Generate content using ChatGPT/Gemini
- Create poster manually
- Refine prompts multiple times
- Send final draft for approval

This process is time consuming and inconsistent.

## Solution

Agent AURA is a personalized AI assistant that:

- Generates AI learning content
- Creates branded posters
- Generates engagement questions
- Maintains AURA style and branding
- Reduces manual effort

## workflow
User
 ↓
Topic Enter
 ↓
Generate
 ↓
FastAPI
 ↓
LLM
 ↓
Poster + Poll + Content
 ↓
Frontend Display
 ↓
User Feedback
 ↓
Revision
 ↓
LLM
 ↓
Updated Output

## project structure 

agent-aura-frontend/

│
├── app.py
│
├── pages/
│   ├── 1_Generate.py
│   ├── 2_History.py
│   ├── 3_Campaigns.py
│
├── components/
│   ├── navbar.py
│   ├── poster_viewer.py
│   ├── poll_viewer.py
│   ├── feedback_form.py
│   ├── content_viewer.py
│
├── services/
│   ├── api.py
│   ├── auth.py
│
├── utils/
│   ├── session.py
│   ├── logger.py
│   ├── constants.py
│
├── assets/
│   ├── logo.png
│
├── logs/
│   └── app.log
│
├── requirements.txt
│
└── .env


## Future Scope

- Approval Dashboard
- Analytics
- Automated Scheduling
- Multi-language Support
