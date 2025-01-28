# 🌟 PDF Analyzer - Your AI Assistant for summarization

## 🌟 Overview
PDF Analyzer is an AI-powered Streamlit application designed to simplify the process of analyzing and summarizing PDF files. By leveraging the JamAI API, this app extracts text from uploaded PDFs, processes it for summarization, and provides an option to download a detailed report in a .docx format. Whether you're a professional or a student, PDF Analyzer streamlines your workflow for document analysis.

---

## 🚀 Features

1. **PDF Text Extraction**: Extracts text content from uploaded PDF files using the PyPDF2 library.
2. **AI-Powered Summarization**: Utilizes the JamAI API to generate concise and meaningful summaries of the uploaded documents.
3. **Customizable Reports**: Automatically generates a .docx report containing the extracted summary, available for download.
4. **User-Friendly Interface**: Intuitive design built with Streamlit, styled with custom CSS for a modern look.
5. **Environment Variable Integration**: Securely manages API keys and project IDs using `dotenv`.

---

## 🛠️ Technologies Used

1. **Python**: Core programming language for the application.
2. **Streamlit**: Framework for building the web-based user interface.
3. **PyPDF2**: Library for extracting text from PDF files.
4. **JamAI**: AI API used for summarizing PDF text.
5. **docx**: Library for generating Word (.docx) files.
6. **dotenv**: Used for managing environment variables securely.

---

## 📦 Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or higher
- pip (Python package manager)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/iqbalzulsafari/PDF-Analyzer.git
   cd PDF-Analyzer
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up environment variables:
   - Create a `.env` file in the project root.
   - Add your JamAI `ACCESS_TOKEN` and `PROJECT_ID`:
     ```env
     ACCESS_TOKEN=your_access_token_here
     PROJECT_ID=your_project_id_here
     ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
5. Access the app at `http://localhost:8501` in your browser.

---

## 📄 Usage
1. Upload a PDF file using the file uploader in the app.
2. Click on the **Process Input** button to analyze and summarize the document.
3. View the generated summary on the app interface.
4. Download the final report in .docx format.

---

## 💡 Key Highlights
1. Securely integrates with JamAI using environment variables to protect sensitive information.
2. Ensures seamless text extraction and processing from PDFs using PyPDF2.
3. Provides a visually appealing and responsive UI with custom CSS styling.
4. Streamlines document analysis workflows with fast summarization and report generation.
5. Offers flexible and portable report downloads in a widely supported file format.

---

## 🧑‍💻 Contributors
- [Iqbal Zulsafari](https://github.com/iqbalzulsafari)

---

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🌐 Links
- [GitHub Repository](https://github.com/iqbalzulsafari/PDF-Analyzer)

