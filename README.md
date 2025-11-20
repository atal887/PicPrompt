# PicPrompt

## AI-Powered Image Prompt Generator for Modern Creative Workflows

PicPrompt is an intelligent AI-driven image interpretation platform that allows users to upload an image and instantly generate meaningful prompts, descriptions, and content ideas. Whether you're a designer, writer, or content creator, PicPrompt provides fast visual understanding powered by state-of-the-art AI models. The system includes a clean React frontend and a robust Node.js backend.

## 🚀 Features

### 1. AI Prompt Generator
- **Image Upload Support**: Upload images easily from your system
- **AI-Generated Prompts**: Automatically create detailed prompts using AI
- **Content Insights**: Generate creative descriptions for design and content use
- **Fast & Lightweight**: Optimized for quick response times

## 🛠️ Technology Stack

### Backend
- **Node.js**
- **Express**
- **Multer** for file handling
- **Environment-based** configuration

### Frontend
- **React** (Vite)
- **TailwindCSS**
- **Axios**
- **JavaScript** ES6+

### AI 
- **External AI API** (e.g., OpenAI/Gemini/Custom model) for image prompt generation

## 📁 Project Structure

```
PicPrompt/
│
├── client/                             # React Frontend
│   ├── public/                         # Static public assets
│   │
│   └── src/
│       ├── assets/                     # Icons, images, illustrations
│       ├── components/                 # Reusable UI components
│       ├── pages/                      # Home, Result, BuyCredit
│       ├── App.jsx                     # Root React component
│       └── main.jsx                    # Entry point for Vite
│
├── server/                             # Node.js Backend
│   ├── controllers/                    # API logic for processing images
│   ├── routes/                         # Endpoints for client communication
│   ├── utils/                          # Helper functions
│   └── index.js                        # Main Express server file
│
├── README.md                           # Documentation
└── project.zip                         # (Optional local file)
```

## 🚀 Installation & Setup

### Prerequisites
- Node.js (16+)
- npm or yarn
- API key for AI model (if required)

### 1. Clone the Repository
```bash
git clone https://github.com/atal887/Picprompt.git
cd Picprompt
```

### 2. Setup the Frontend
```bash
cd client
npm install
npm run dev
```

### 3. Setup the Backend
```bash
cd ../server
npm install
npm start
```

### 4. Run the Application
The application will be available at:
- **Frontend**: http://localhost:5173
- **Backend**: http://localhost:5000

## 🔧 API Endpoints

### Misc
- `GET /api/health` -  Server Health check

### Image Processing
- `POST /api/prompt/generate ` — Upload image & generate prompt

## 🎨 User Interface

- Clean & modern design
- Drag & drop file uploading (optional)
- Image preview container
- Results displayed with styled formatting
- Mobile-responsive layout

## 🔒 Privacy & Security

- Images processed temporarily (no storage)
- Local-only environment variables
- No sensitive data logged
- CORS-protected backend

## 🚀 Future Enhancements

- Multi-image prompt generation
- Downloadable result summaries
- User authentication
- Advanced AI models for deeper visual analysis
- Dark/light mode

## 📄 License

This project is licensed under the MIT License.

---

**Transform images into ideas instantly.**