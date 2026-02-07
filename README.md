# IKAAD (Intelligent Knowledge Assistant for Academic & Technical Documents)

## About The Project

IKAAD is an AI-powered **study assistant** designed to deeply understand and work over your academic and technical materials. Whether you provide PDFs, PPTs, DOCX files, or (in the future) videos, IKAAD intelligently extracts knowledge to provide concept-level, source-grounded assistance. 

Instead of just presenting raw facts, IKAAD acts as a real-time tutor that helps generate concise summaries, creates tailored explanations based on your proficiency (Beginner, Intermediate, Advanced), tests your knowledge using dynamic flashcards and quizzes, and continuously builds out customized learning paths. 

The core philosophy of IKAAD is **User-Confirmed Generation**: the AI works alongside you, taking your syllabus and resources, proposing a plan, and requiring your confirmation before executing intensive operations.

## Features

- **Multi-Format Summarization**: Upload PDFs, PPTs, or DOCX files for instant insights.
- **Level-Based Explanations**: Ask for explanations tailored to Beginner, Intermediate, or Advanced levels with visual references from documents.
- **Dynamic Testing**: Automatic generation of flashcards and quizzes to test your grasp on the subject.
- **Grounded Doubt Clearing**: Back-and-forth conversational agent that grounds its answers purely in the provided source material.
- **Sample Paper Generation**: Create realistic exams combining past papers constraints with current syllabus coverage.
- **Interactive Learning Plans**: Supply a textbook, and the AI plans chapter-by-chapter progression.
- **Future Video Support**: Upcoming transcript extraction and summarization for recorded lectures and YouTube videos.
- **Future Voice Chat**: Simulate viva and technical interviews interactively.

## Technical Architecture

This application uses a modular architecture:
- **Frontend**: A React.js Single Page Application created with Vite.
- **Backend**: A FastAPI Python server heavily utilizing LangChain, Groq LLMs, `sentence-transformers`, and `faiss-cpu` for Retrieval-Augmented Generation (RAG).

*Full feature specification, confirmation flows, and the phased roadmap can be found in `docs/study-assistant-vision.md`.*
