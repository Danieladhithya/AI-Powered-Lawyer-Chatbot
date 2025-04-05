# AI-Powered-Lawyer-Chatbot
An AI-powered virtual legal assistant designed to help users understand and navigate the Indian legal system. The chatbot intelligently answers legal queries using the Indian Penal Code (IPC) and provides additional support through a DIY Legal Kit for common legal needs. It integrates NLP and similarity-matching algorithms to provide accurate, section-specific legal responses with a user-friendly interface.

 Key Features:
🔍 Legal Query Understanding:
Uses NLP to interpret natural language legal questions and extract relevant keywords and context.

📖 IPC Section Search & Matching:
Scans IPC documents and returns the most relevant sections using TF-IDF vectorization and cosine similarity.

💬 Context-Aware Chatbot Responses:
Returns section numbers, titles, and legal details with clarity to help users understand the law behind their query.

📄 DIY Legal Kit:
Provides downloadable templates and checklists for common legal processes like:

Filing an FIR

Drafting a complaint

Legal notice templates

Tenant agreements, etc.

🧑‍⚖️ Legal Support Guidance:
Offers information on how to approach a legal issue, including:

When to consult a lawyer

Steps to file a case

Relevant government/legal portals


Data Used:
IPC Sections.pdf — Core structure of IPC laws

IPC part 2.pdf & IPC part 3.pdf — In-depth legal content for referencing in responses

Tech Stack:
Python

Hugging Face Transformers (optional LLM integration)

Scikit-learn

Pandas, NLTK

PyPDF2 (for extracting text from IPC documents)

Objectives:
Make legal information accessible to the general public

Automate legal support for frequently asked questions

Empower users with self-help tools via the DIY Legal Kit

Create a foundation for future integration with real-time legal databases or LLMs

