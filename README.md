# Face Recognition Attendance System - FastAPI Backend

This is the FastAPI backend for the Face Attendance System. It supports:

- 📸 Face Registration
- 👁️ Real-time Face Recognition
- 📜 Attendance Logging
- ❌ Automatic Absentee Marking

## Folder Structure

- `main.py`: Starts the FastAPI app
- `routers/`: API route handlers
- `services/`: Core face recognition logic
- `dataset/`: User face images
- `model/`: Trained LBPH model
- `haarcascade/`: Face detection XML
- `attendance.csv`: Attendance log file

## Run Locally

```bash
pip install -r requirements.txt
uvicorn main:app --reload

