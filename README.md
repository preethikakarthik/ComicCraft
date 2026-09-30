# ComicCraft - AI Comic Story Creator

An AI-powered comic generator built with FastAPI, Gemini & Stable Diffusion.

### Tech Stack
- Frontend: HTML, CSS, Jinja2
- Backend: FastAPI (Python)
- AI Models: Gemini 1.5 Flash, Gemini 1.5 Pro, Stable Diffusion v1-5
- PDF Export: FPDF

### Workflow
User Input -> FastAPI -> Gemini Flash (5-panel outline) -> Gemini Pro (Story) -> Stable Diffusion (Images) -> Layout Builder

### How to Run
pip install -r requirements.txt
uvicorn app.main:app --reload

Project by SmartBridge - SmartInternz
