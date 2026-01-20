# RoadSense AI

RoadSense AI is a full-stack generative AI agent that interprets painted utility
markings on roads using Pydantic AI and OpenRouter models.

## Tech Stack
- Backend: FastAPI, Pydantic AI, EasyOCR
- Frontend: Next.js, Tailwind CSS
- AI Model: OpenRouter (Gemini Flash Lite)
- Deployment: Render (backend) + Vercel (frontend)

## How It Works
1. User uploads a road image
2. Backend extracts text using OCR
3. Pydantic AI agent analyzes the text
4. Structured insights are returned to the UI

## Live Demo
Frontend: <your-vercel-link>
Backend: <your-render-link>
