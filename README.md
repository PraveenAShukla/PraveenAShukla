
## 🔧 Tech Stack Overview

| **Component**          | **Technologies** |
|------------------------|------------------|
| 🔹 **Backend Framework**    | FastAPI, Flask |
| 🔹 **Agent Orchestration** | LangGraph |
| 🔹 **Knowledge Storage**   | Qdrant Vector Database |
| 🔹 **Medical Imaging**     | Computer Vision Models (PyTorch) |
|                          | • Brain Tumor – Object Detection |
|                          | • Chest X-ray – Image Classification |
|                          | • Skin Lesion – Semantic Segmentation |
|                          | • **Oral Cancer – Semantic Segmentation** |
| 🔹 **Guardrails**          | LangChain |
| 🔹 **Speech Processing**   | Eleven Labs API |
| 🔹 **Frontend**            | HTML, CSS, JavaScript |
| 🔹 **Deployment**          | Docker, CI/CD Pipeline |

Run the Application

Open **two terminal windows** in the **same project directory** and **activate the same virtual environment**. Then run the following commands **simultaneously**:

```bash
# Terminal 1 – Start the FastAPI backend
uvicorn api.fastapi_backend:app --reload

# Terminal 2 – Start the frontend or app logic
python app.py

---
