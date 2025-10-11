# Sparq Voice Recognition API

- **Stack:** Python, FastAPI, Uvicorn, Docker, Whisper, FFmpeg
- **Endpoints:** `POST /api/v1/transcribe`, `GET /` (Web UI), `GET /docs` (OpenAPI Spec)
- **Usage:** `docker build -t sparq-vr . && docker run -d -p 8000:8000 -e WHISPER_MODEL=base --name sparq-app sparq-vr`
- **Tests:** `pytest`


![img.png](docs/img.png)!