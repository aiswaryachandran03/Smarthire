# SmartHire – AI-Powered Recruitment System

SmartHire is an intelligent, AI-driven recruitment platform designed to automate and enhance the hiring process. It streamlines resume screening, job matching, skill assessments, exam proctoring, and AI-led interviews — offering a complete end-to-end hiring solution for companies.

## 🚀 Project Overview

Traditional recruitment is slow, manual, and prone to human bias. SmartHire solves these challenges by integrating automation, AI, and computer vision to support faster and more accurate hiring decisions.

Built using Python, Django, AI APIs, OpenCV, and SQLite, SmartHire reduces manual workload for HR teams and improves the experience for both job seekers and employers.

### 🎯 Key Features
✔️ **AI Resume Screening**

- Extracts text from PDFs using PyMuPDF

- Uses spaCy NLP to identify skills, experience, organizations, dates

- Generates match scores between job descriptions and candidate profiles

✔️ **Smart Job Matching**

- AI-based keyword extraction

- Ranking based on resume–job similarity

- Prevents duplicate job applications

✔️ **AI-Generated Exams**

- Uses OpenAI GPT-3.5 to generate dynamic questions

- Supports manual and automated question creation

- Auto-evaluates answers and stores results

✔️ **AI Proctored Online Exams**

- OpenCV + YOLOv8 → detects phones, multiple people, fraud

- dlib → detects faces, eye movements, blinking

- Flags suspicious activity and logs violations

✔️ **AI Interview System**

- Llama3/ChatGPT-powered chatbot

- Asks adaptive interview questions

- Voice-based interaction

- Auto-evaluates candidate responses

✔️ **Performance Report Generation**

- Generates detailed PDF reports using ReportLab

- Includes scores, feedback, and violation logs

## 🏗️ System Architecture

SmartHire is designed with a three-tier architecture:

Frontend: HTML, CSS, JavaScript

Backend: Django + Django REST Framework

Database: SQLite

AI Modules: OpenAI, Groq, spaCy, OpenCV, YOLO, dlib

## 🔧 Tech Stack
Layer	Technologies
Frontend	HTML, CSS, JS, Web Speech API
Backend	Python, Django, DRF
AI/NLP	OpenAI GPT-3.5, Groq LLaMA, spaCy
Computer Vision	OpenCV, dlib, YOLOv8
Database	SQLite
PDF/Reports	ReportLab, PyMuPDF

## 🛠️ Core Modules
🔹 **Resume Processing**

- PDF extraction

- NLP-based entity recognition

- Skill extraction

- Match score calculation

🔹 **Job Management**

- Post jobs

- Apply for jobs

- Real-time application tracking

🔹 **Exam System**

- AI question generation

- Auto-evaluation

- AI proctoring

- Violation monitoring

🔹 **Interview System**

- AI chatbot interviewing

- Dynamic question transitions

- Voice input/output

## 📊 Results

- Reduced manual effort for resume screening

- Faster candidate shortlisting

- Unbiased AI evaluation

- Secure and monitored exam environment

- Automated end-to-end hiring pipeline

## ⚠️ Current Limitations

- Limited browser support for voice features (no Firefox)

- AI chatbot may misinterpret nuanced responses

- No real-time employer notifications yet

- Pre-recorded avatar lacks real lip-sync

## 🔮 Future Enhancements

- Upgrade to GPT-4 / improved LLMs

- Real-time lip-syncing for chatbot avatars

- Broader browser support

- Automated email/SMS notifications

- Sentiment analysis in interviews

- Enhanced security (ID verification, encrypted proctoring footage)

🏁 Conclusion

SmartHire demonstrates how AI, NLP, and computer vision can transform recruitment by making it faster, fairer, and more efficient. With automated screening, expert-level assessments, proctoring, and chatbot interviews, the platform delivers a modern and scalable alternative to traditional hiring workflows.
