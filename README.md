# 🤖 Interview Question Generator
This is a Streamlit web application that uses Langchain and OpenAI to automatically generate interview questions and answers from an uploaded document (PDF or DOCX).

---

### ✨ Features:
* **📄 Supports PDF & DOCX:** Upload job descriptions or other materials.

* **🧠 Smart Q&A Generation:** Uses LLMs to create relevant questions and find answers within the text.

* **💾 CSV Export:** Download the generated Q&A pairs for offline use.

* **🎨 Simple UI:** Clean and easy-to-use interface.

---

### 🛠️ Technologies Used:
**Framework:** Streamlit

* **LLM Orchestration:** Langchain

* **AI Model:** OpenAI (GPT-3.5-Turbo)

* **Vector Store:** FAISS

* **Document Parsers:** PyPDFLoader, python-docx

---

### 🚀 How to Run
Follow these steps to get the application running locally.

1.  **Clone the repository:**
    ```bash
    git clone git@github.com:kathiravanthilagar31/Job_Interview_QA_Generator.git
    cd Job_Interview_QA_Generator
    ```

2.  **Create a virtual environment (recommended):**
    It's good practice to use a virtual environment to manage project dependencies.
    ```bash
    python -m venv venv
    # On Windows:
    .\venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate
    ```

3.  **Install Python dependencies:**
    With your virtual environment activated, install all required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
    
4.  **Set up your OpenAI API Key:**
    Your application requires an OpenAI API key to interact with the LLM and embedding models.
    * Create a new file named `.env` in the **root directory** of your project (the same directory as `app.py` and `requirements.txt`).
    * Add your OpenAI API key to this file in the following format:
        ```
        OPENAI_API_KEY="your_openai_api_key_here"
        ```
        (Replace `"your_openai_api_key_here"` with your actual OpenAI API key.)

5.  **Run the Streamlit application:**
    From the root directory of your project (where `app.py` is located), execute the following command:
    ```bash
    streamlit run app.py
    ```
    This command will start the Streamlit server, and your app will automatically open in your default web browser.

---
