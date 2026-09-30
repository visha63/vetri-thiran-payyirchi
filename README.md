# ComicCraft - AI Comic Story Creator

FastAPI-based project structure following the uploaded ComicCraft project document.

## Workflow
User prompt -> Gemini Flash outline -> Gemini Pro narration/dialogue ->
Stable Diffusion illustrations -> layout -> PDF export.

## Main routes
- `/`
- `/generate`
- `/generate-comic/json`
- `/export-success`
- `/test-image`

## Configuration
Copy `.env.example` to `.env` and add the required API keys.

## Run
`uvicorn app.main:app --reload`

Open `http://127.0.0.1:8000`
