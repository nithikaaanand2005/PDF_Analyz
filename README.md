# PDF Analyzer Enhanced (Expert Examiner AI)

An intelligent full-stack application that analyzes PDF documents to generate exam-style questions and answer user queries using context from the document.

## 🚀 Features

- **PDF Analysis**: Upload and parse text from PDF documents instantly in the browser.
- **AI Question Generator**: Automatically generate questions based on the PDF content.
  - Supports multiple types: **1-Mark**, **Short Answer**, and **Long Answer**.
  - Customizable interaction.
- **Q&A Chat**: Ask functionality to query specific details from the uploaded PDF.
- **Robust Error Handling**: Includes a mock response fallback system if the AI API is unavailable.
- **Modern UI**: Built with React and Material UI for a polished user experience.

## 🛠️ Tech Stack

- **Frontend**: React.js, Material UI (MUI), pdfjs-dist
- **Backend**: Node.js, Express.js
- **AI Integration**: OpenAI API (GPT-3.5-turbo)

## 📂 Project Structure

```
pdf-analyzer-enhanced/
├── backend/            # Express server & API endpoints
├── frontend/           # React client application
└── README.md           # Project documentation
```

## ⚡ Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### 1. Backend Setup

The backend handles API requests and communicates with OpenAI.

```bash
cd backend
npm install
```

**Configuration**:
Create a `.env` file in the `backend` directory and add your OpenAI API Key:

```env
OPENAI_API_KEY=your_api_key_here
```

**Start Server**:
```bash
npm start
```
*The backend will run on `http://localhost:8001`*

### 2. Frontend Setup

The frontend is a React application.

```bash
cd frontend
npm install
```

**Start Client**:
```bash
npm start
```
*The application will open at `http://localhost:3000`*

## 📝 Usage

1. Open the app in your browser.
2. Click **"Upload PDF"** to select a document.
3. Use the **"Generate Questions"** section to create a quiz based on the text.
4. Use the **"Ask a Question"** section to chat with your PDF.

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes.
4. Push to the branch.
5. Open a Pull Request.

## 📄 License

This project is open-source and available under the content license.
