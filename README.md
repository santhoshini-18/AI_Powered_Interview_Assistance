# AI_Powered_Interview_Assistance
🤖 AI-Powered Interview Assistant

An AI-powered interview practice platform that helps users prepare for technical and communication-based interviews through interactive voice conversations, adaptive questions, and personalized AI-generated feedback.

The application simulates a real interview experience by asking questions, listening to spoken answers, converting voice responses into text, and evaluating the candidate's performance using Google Gemini.

✨ Features

AI-Powered Interviews: Conduct interactive interviews using Google Gemini.

Voice-Based Interaction: Listen to interview questions using natural AI-generated speech.

Speech-to-Text Conversion: Automatically convert spoken answers into text.

Adaptive Questioning: Generate follow-up questions based on the candidate's previous answers.

Multiple Interview Topics: Choose from different subjects, including:

Self Introduction

Generative AI

Python

English

HTML

CSS

Personalized Feedback: Receive AI-generated feedback based on actual interview responses.

Performance Score: Get a candidate score out of 5.

Areas of Improvement: Identify weaknesses and understand where to improve.

Interactive User Interface: Simple, modern, and responsive interface.

🛠️ Technologies Used

**Frontend**

HTML5

CSS3

JavaScript

Tailwind CSS

Backend

Python

Flask

Flask-CORS

AI & Voice Technologies

Technology

Purpose

Google Gemini

AI-powered interview questions and feedback

Murf AI

Text-to-Speech (TTS) for generating interviewer voice

AssemblyAI

Speech-to-Text (STT) for converting recorded answers into text

LangChain

Integration with the Gemini language model

LangGraph

Agent creation and conversation memory

Other Libraries

Requests

Python-dotenv

AssemblyAI Python SDK

🏗️ Project Architecture

The application follows a frontend-backend architecture with AI and voice-processing integrations.

                 USER
                   |
                   v
          FRONTEND (HTML, CSS, JS)
                   |
                   v
             FLASK BACKEND
                   |
          +--------+--------+
          |        |        |
          v        v        v
       GEMINI    MURF AI  ASSEMBLYAI
          |        |        |
          v        v        v
     Questions   Voice    Speech-to-
     & Feedback  Output    Text
          |        |        |
          +--------+--------+
                   |
                   v
           INTERVIEW RESPONSE
                   |
                   v
           PERSONALIZED FEEDBACK

⚙️ How It Works

Select Interview Topic: The user selects a subject from the available topics.

Start Interview: The backend initializes an AI interviewer using Google Gemini.

Generate Questions: Gemini generates interview questions based on the selected topic.

Voice Generation: Murf AI converts the generated questions into natural speech.

Record Answers: The user records their answers using the microphone.

Speech Recognition: AssemblyAI converts the recorded audio into text.

Adaptive Interview: Gemini analyzes the response and generates the next relevant question.

Generate Feedback: After completing the interview, Gemini evaluates the conversation and generates:

Candidate score (out of 5)

Detailed feedback

Areas of improvement
🎯 Project Objectives

Make interview preparation more interactive and accessible.

Provide a realistic voice-based interview experience.

Use Generative AI to create dynamic interview questions.

Improve communication and technical interview skills.

Provide personalized feedback to help candidates improve their performance.

🔮 Future Enhancements

User authentication and profile management.

Interview history and performance tracking.

Resume-based interview question generation.

More technical interview categories.

Advanced speech and communication analysis.

Detailed performance analytics and progress reports.

Database integration to store interview results.

👩‍💻 Developed By

Santhoshini Amberkar

AI-Powered Interview Assistant

⭐ Support

If you find this project interesting or useful, consider giving this repository a ⭐ on GitHub!

Built with Python, Flask, JavaScript, Google Gemini, Murf AI, and AssemblyAI.
