# 🌌 AI-Powered 3D Data Explorer

An interactive AI-powered 3D data visualization tool that combines **Python (ML/DL)** and **Three.js (3D graphics)**.  
It transforms boring datasets into an interactive 3D galaxy with clustering, AI insights, neural network visualization, time-travel animations, and even **VR/AR exploration**.

---

## ✨ Features
- 📂 **Dataset Upload** → Upload CSV/JSON files for analysis.
- 🤖 **Machine Learning Pipeline** → Dimensionality reduction (PCA/UMAP/Autoencoders), clustering (KMeans, DBSCAN).
- 🧠 **AI Insights** → Automatic cluster summaries using Transformers/LLMs.
- 🌌 **3D Data Galaxy** → Explore datasets as glowing points in 3D space with Three.js.
- 🔮 **Neural Network Visualizer** → Watch an NN model come alive in animated 3D layers.
- ⏳ **Time-Travel Mode** → Animate datasets evolving over time.
- 🕶️ **VR/AR Mode** → Walk inside your data using WebXR.

---

## 🛠 Tech Stack
**Backend (Python + ML/DL):**
- FastAPI / Flask
- Pandas, NumPy, Scikit-learn
- PyTorch (Autoencoders, NN)
- HuggingFace Transformers

**Frontend (Visualization):**
- Three.js (3D rendering)
- WebXR (VR/AR support)
- Vanilla JS / React (optional for UI)

---

## 📂 Project Structure
```
ai-3d-data-explorer/
│── backend/
│   ├── app.py              # FastAPI backend
│   ├── ml_pipeline.py      # Dim reduction + clustering
│   ├── nn_visualizer.py    # Neural network training + data
│   ├── summarizer.py       # HuggingFace / LLM insights
│   └── requirements.txt
│
│── frontend/
│   ├── index.html
│   ├── app.js              # Main Three.js app
│   ├── 3d_scatter.js       # Data explorer view
│   ├── nn_visualizer.js    # Neural net animation
│   ├── timeline.js         # Time-travel mode
│   └── vr_mode.js          # WebXR VR experience
│
│── datasets/               # Sample datasets
│── docs/                   # Screenshots, GIFs, demo videos
│── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repo
```bash
git clone https://github.com/<your-username>/ai-3d-data-explorer.git
cd ai-3d-data-explorer
```

### 2️⃣ Backend Setup (Python)
```bash
cd backend
pip install -r requirements.txt
uvicorn app:app --reload
```

### 3️⃣ Frontend Setup (Three.js)
- Open `frontend/index.html` in browser  
*(or serve with a local web server like VS Code Live Server)*

---

## 📌 Roadmap
- [ ] Phase 1: Core 3D scatter plot + clustering  
- [ ] Phase 2: Neural network visualizer  
- [ ] Phase 3: Time-travel mode  
- [ ] Phase 4: VR/AR exploration  

See project tasks here: [GitHub Projects](../../projects)

---

## 🏷️ Badges
![GitHub issues](https://img.shields.io/github/issues/vEEr6057/ai-3d-data-explorer)
![GitHub forks](https://img.shields.io/github/forks/vEEr6057/ai-3d-data-explorer)
![GitHub stars](https://img.shields.io/github/stars/vEEr6057/ai-3d-data-explorer)
![GitHub license](https://img.shields.io/github/license/vEEr6057/ai-3d-data-explorer)

---

## 📸 Demo (Coming Soon)
Screenshots and GIFs will go here once features are ready.

---

## 📜 License
MIT License © 2025 vEEr6057  

---

## 👨‍💻 Author
- **Veer Shah**   
