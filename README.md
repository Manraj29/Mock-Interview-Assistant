# 🧠 Mock Interview Assistant & Resume Analysis

> **📁 Note:** The working module is located in the `login/` folder.

## 📌 Overview

This project is an AI-powered web application developed during a hackathon that offers two primary functionalities:

- **Mock Interview Assistant** – Simulates a job interview based on your resume and selected job role, providing real-time AI feedback and performance scoring.
- **Chat with Resume** – Allows users to upload a resume and interact with it using natural language. The Gemini LLM API responds with contextual answers based on the uploaded resume.

Built using **Python**, integrated with **Gemini LLM**, and backed by **Firebase** for authentication and database management.

---

## ✨ Features

### 🔹 Mock Interview Assistant

- 🔐 **Firebase Authentication** – Secure login and user session management.
- 📄 **Resume Upload** – Upload resume in PDF format.
- 💼 **Job Role Selection** – Choose the job position you're targeting.
- ❓ **Dynamic Question Generation** – AI generates personalized interview questions.
- 🎤 **Voice-based Answering** – Users respond via speech (TTS + Speech-to-Text).
- 📝 **Performance Evaluation** – Responses are evaluated using Gemini API to provide:
  - Accuracy and clarity  
  - Technical knowledge  
  - Communication skills  
  - Overall performance score  
  - Detailed feedback and suggestions for improvement

### 🔹 Chat with Resume

- 📄 **PDF Parsing** – Extracts and parses text from uploaded resumes.
- 💬 **Conversational Resume Q&A** – Users can ask questions such as:
  - “What skills do I have listed?”
  - “What is my most recent work experience?”
  - “Am I suitable for a data analyst role?”
- 🧠 **Powered by Gemini API** – Provides context-aware answers from the resume.
- 🔁 **Session-based Chat History** – Maintained during session but erased on refresh.

---

## Outputs
Register & Login
<img width="1369" height="623" alt="image" src="https://github.com/user-attachments/assets/1a095bf4-7566-4684-b35a-0d0e4c1a1637" />
Main Page - Upload PDF & Select role
<img width="1370" height="621" alt="image" src="https://github.com/user-attachments/assets/49027375-9180-4642-8a71-47a5caea0e75" />
Mock Interview in progress
<img width="1367" height="627" alt="image" src="https://github.com/user-attachments/assets/c32436c4-3ad8-415a-8e60-595e80b10758" />
Results of Interview / Feedback
<img width="1367" height="623" alt="image" src="https://github.com/user-attachments/assets/d03a3206-fba3-45d1-b07f-2db0ddc441ae" />
<img width="1364" height="621" alt="image" src="https://github.com/user-attachments/assets/d19d5864-c849-4d14-9125-803cb4757b34" />
Chat with Resume Module
<img width="1363" height="622" alt="image" src="https://github.com/user-attachments/assets/29610c79-e2d5-490a-82fe-0a8af2afc12f" />
<img width="1373" height="612" alt="image" src="https://github.com/user-attachments/assets/3119fcb5-86b5-4cb2-a1e2-c13221761e67" />



## 🛠 Tech Stack

| Category        | Tools & Frameworks                            |
|----------------|-----------------------------------------------|
| 🧠 LLM          | Gemini API (Google's Generative AI)          |
| 🔙 Backend      | Python                                        |
| 🔐 Auth & DB    | Firebase Authentication                      |
| 🎤 Speech       | TTS                                          |
| 📄 File Handling| PyPDF2                                       |
| 🌐 Frontend     | StreamLit                                    |

---

## ⚙️ Working

The user begins by logging into the platform using Firebase Authentication. Once authenticated, they can upload their resume in PDF format and select a desired job role. Based on this input, the application uses AI to generate personalized mock interview questions tailored to the job role and resume content. The user answers these questions verbally using speech input, which is transcribed via Speech-to-Text. All responses are collected and sent to the Gemini API for evaluation. The API returns a detailed performance report, including a score breakdown, analysis of communication and technical skills, and suggestions for improvement.

In the "Chat with Resume" module, users can upload their resume, which is parsed to extract relevant information. They can then ask contextual questions about their own resume, such as inquiries about listed skills or experience. The Gemini API provides intelligent, resume-aware answers. The chat history is maintained for the session but is erased upon refresh.

---

## 👨‍💻 Team Details
- Manraj Singh Virdi (Leader)
- Disha Bhatt
- Tanvi Sangle
- Deven Bhagtani
