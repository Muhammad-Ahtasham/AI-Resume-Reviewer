# AI Resume Reviewer

AI Resume Reviewer is a web application that allows users to upload their resume in PDF format and receive automated, AI-powered analysis, feedback, and suggestions for improvement.

## Features
- Upload your resume (PDF)
- Automatic extraction of resume sections
- AI-generated feedback and suggestions
- Modern, responsive UI
- Fast, server-side PDF parsing and analysis

## Tech Stack
- **Frontend:** Next.js, React, Tailwind CSS, Axios
- **Backend:** Node.js, Express, LangChain, OpenAI, PDF parsing
- **Deployment:** Netlify

## Project Structure
```
/ (root)
├── client/   # Frontend (Next.js app)
├── server/   # Backend (Express API)
└── netlify.toml  # Deployment config
```

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn
- OpenAI API key (for backend analysis)

### 1. Clone the repository
```bash
git clone https://github.com/Muhammad-Ahtasham/AI-Resume-Reviewer.git
cd AI-Resume-Reviewer
```

### 2. Install dependencies
#### Frontend
```bash
cd client
npm install
```
#### Backend
```bash
cd ../server
npm install
```

### 3. Set up environment variables
Create a `.env` file in the `server/` directory with your OpenAI API key:
```
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Run the application locally
#### Start the backend server
```bash
cd server
npm start
```
#### Start the frontend (in a new terminal)
```bash
cd client
npm run dev
```

- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## Usage
1. Open the frontend in your browser.
2. Upload your resume (PDF format only).
3. View extracted sections, AI feedback, and suggestions.

## Deployment
- The project is configured for Netlify deployment. See `netlify.toml` for build settings.
- To deploy, connect your repository to Netlify and follow their deployment instructions.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements or bug fixes.

## License
[MIT](LICENSE) (add a LICENSE file if needed)

---

**Made with ❤️ for better resumes!**
