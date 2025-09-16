# Conversation Management & Classification using Groq API

This repository contains my submission for the **Conversation Management & Classification Assignment**.  
The notebook demonstrates the use of **Groq’s OpenAI-compatible SDK** for function calling and completions, implementing summarization logic, and JSON schema classification in a clean and reproducible workflow.

---

## Project Overview
The goal of this project is to build a conversation management pipeline that can:
1. Perform **k-th run summarization** of conversations.  
2. Classify and extract structured data using a **JSON schema**.  
3. Demonstrate correctness using **Groq API** without external frameworks.  
4. Present results in a **Google Colab notebook** with clear code, outputs, and documentation.  

---

##  Requirements
- Python 3.8+  
- [Groq API Key](https://console.groq.com/)  
- Libraries:
  - `requests`
  - `openai` (Groq’s compatible SDK)

**Note:** No frameworks (Flask, FastAPI, LangChain, etc.) were used, as per assignment requirements.

## Repository Structure
Conversation_Management_Groq_Assignment/
── AI_Conversation_Management_and_Classification_UPDATED.ipynb # Main Colab notebook
── README.md # Project documentation

---



## Running the Notebook

1. Open the notebook in **Google Colab**:
   - Upload `AI_Conversation_Management_and_Classification_UPDATED.ipynb` to [Colab](https://colab.research.google.com/).
   - Alternatively, open directly from GitHub using Colab’s URL import.

2. Set your **Groq API key** inside the notebook:
   ```python
   import os
   os.environ["GROQ_API_KEY"] = "your_api_key_here"

3. Run the notebook cells in order to:
    Generate conversation summaries
    Perform classification
    Validate outputs

   
Example Outputs
Summarized conversations (k-th run).
Classified JSON results extracted from conversations.
Visible outputs in each cell for easy evaluation.





