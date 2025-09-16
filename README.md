# Conversation Management & Classification using Groq API  

## 📌 Objective  
This project demonstrates two core tasks using the **Groq API** (OpenAI-compatible SDK):  
1. **Conversation Management with Summarization**  
2. **JSON Schema Classification & Information Extraction**
   
The assignment is implemented in a **Google Colab notebook** and pushed to GitHub.  

## 🔹 Tasks Implemented  

### Task 1: Managing Conversation History with Summarization  
- Maintained a running history of user–assistant chats.  
- Implemented **summarization** of conversation history to keep it concise.  
- Added truncation options:  
  - Limit by number of turns (`n` messages).  
  - Limit by character/word length.  
- Implemented **periodic summarization** (after every `k`-th run).  
- Demonstrated functionality with multiple conversation samples showing:  
  - Outputs at different truncation settings.  
  - Summarization after every 3rd run.  

### Task 2: JSON Schema Classification & Information Extraction  
- Created a JSON schema to extract 5 details from chats:  
  - **Name, Email, Phone, Location, Age**.  
- Used **OpenAI function calling with Groq API** for structured extraction.  
- Demonstrated parsing of 3+ sample chats.  
- Validated outputs against the schema.  

## 🔹 Tools & Requirements  
- **Language**: Python (only standard libraries, no frameworks).  
- **API**: Groq API (OpenAI-compatible client).  
- **Notebook**: Google Colab (clean, documented, with outputs). 
