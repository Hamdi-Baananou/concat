# LEOPARTS - Intelligent Parts Information Assistant

A Streamlit-based application that combines document processing, chatbot capabilities, and intelligent information extraction for parts management.

## Features

- 💬 **Interactive Chatbot**: Ask questions about parts and specifications
- 📄 **Document Processing**: Upload and process PDF documents
- 🔍 **Intelligent Search**: Vector-based search for relevant information
- 🤖 **AI-Powered**: Powered by Groq LLM for accurate responses

## Prerequisites

- Python 3.8+
- Streamlit
- Groq API key
- Supabase account and credentials

## Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd concatinate
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
Create a `.env` file in the project root with:
```
GROQ_API_KEY=your_groq_api_key
SUPABASE_URL=your_supabase_url
SUPABASE_SERVICE_KEY=your_supabase_service_key
```

## Usage

1. Start the application:
```bash
streamlit run main.py
```

2. Access the application at `http://localhost:8501`

3. Use the sidebar to navigate between:
   - Home
   - Ask Questions (Chatbot)
   - Upload Documents

## Project Structure

```
concatinate/
├── main.py              # Main application entry point
├── chatbot.py           # Chatbot functionality
├── app.py              # Document processing app
├── config.py           # Configuration settings
├── requirements.txt    # Python dependencies
├── packages.txt        # System dependencies
└── .env               # Environment variables (not in repo)
```

## Dependencies

- Streamlit: Web application framework
- Groq: LLM provider
- Supabase: Database and authentication
- Sentence Transformers: Text embeddings
- Playwright: Web automation
- Other dependencies listed in `requirements.txt`

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

[Your chosen license]

## Support

For support, please [contact details or issue tracker link] 