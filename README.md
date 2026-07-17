📄 Gemini Document Analyzer

An AI-powered Document Analyzer that uses Google Gemini to extract text, summarize documents, answer document-based questions, and generate audio summaries. The application supports PDF and image files through an interactive Gradio interface.

🚀 Features

- 📄 Upload PDF and image documents
- 🔍 Extract text from documents
- 📝 Generate concise document summaries
- ❓ Ask questions based on document content
- 🔊 Convert summaries into speech
- 🤖 Powered by Google Gemini AI
- 🌐 Interactive Gradio interface

🛠️ Technologies Used

- Python
- Google Gemini API
- Gradio
- gTTS (Google Text-to-Speech)
- Google GenAI SDK

📦 Installation

```bash
pip install -r requirements.txt
```

▶️ Run the Application

```bash
python app.py
```

📁 Project Structure

```
Gemini-Document-Analyzer/
│
├── app.py
├── Gemini_Document_Analyzer.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

🔄 Workflow

1. Upload a PDF or image.
2. Select one of the available actions:
   - Extract Text
   - Summarize Document
   - Answer Questions
   - Generate Audio Summary
3. Google Gemini processes the uploaded document.
4. The generated output is displayed in the interface.
5. Audio summaries are produced using Google Text-to-Speech (gTTS).

🌟 Future Enhancements

- Support for Word (.docx) files
- OCR for scanned documents
- Multi-document analysis
- Chat history
- Downloadable summaries
- Multiple language support

Author

Bhavitha Mothe
