_<p align="center">
  <img src="dogman.mp4" width="100%">
</p>
# ⚡ Monster Castle Laboratory — Wolfman Mike’s Music Mastering Magic ⚡

**AI‑Driven Harmonic Mastering Suite** blending ancient resonance principles with modern audio engineering.  
Powered by the **MCP Resonance Memory Core** running inside **Pieces OS**, with live control via **Manus Dashboard**.

---

## 🏰 Overview
The Monster Castle Laboratory is a hybrid digital/physical environment for:
- **Music mastering** with sacred frequency alignment
- **Real‑time resonance analysis** (A4 verification, room mode sweeps, grounding checks)
- **Pyramid harmonic calculations** for Earth‑tuned audio
- **Multi‑client AI orchestration** via MCP in Pieces OS

---

## 🚀 Quick Start

### 1. Clone the repo
```bash
git clone https://github.com/blueharlequin1/wolfman-mike-music-mastering-magic.git
cd wolfman-mike-music-mastering-magic
```

### 2. Install dependencies
**Client (React Dashboard)**
```bash
cd client
npm install
```

**Server (Flask API)**
```bash
cd ../server
pip install -r requirements.txt
```

### 3. Run in dev mode
From the root:
```bash
npm run dev
```
This launches:
- Flask API on port `5000`
- React dashboard on port `3000`

---

## 🔌 MCP + Pieces OS Integration
1. Install **Pieces OS** and enable MCP.
2. Drop the `/resonance-mcp/` folder into your Pieces OS extensions directory.
3. Start the MCP service:
```bash
uvicorn server:app --host 0.0.0.0 --port 39300
```
4. In Manus dashboard `.env`:
```
NEXT_PUBLIC_MCP_SSE_URL=http://localhost:39300/model_context_protocol/2024-11-05/sse
NEXT_PUBLIC_MCP_API_URL=http://localhost:39300
NEXT_PUBLIC_MCP_API_KEY=supersecretkey
```

---

## 📊 Features
- **Resonance Scan** — Detects room modes & logs results
- **Ground Check** — Verifies positive earth grounding
- **A4 Verify** — Confirms tuning reference
- **Pyramid Resonance Report** — Calculates harmonic alignment score
- **Live Dashboard** — Manus UI with charts, KPIs, and alignment meter

---

## 🛠 Tech Stack
- **Frontend:** React, Material UI, Chart.js
- **Backend:** Flask, FastAPI (MCP), SQLite
- **AI Orchestration:** Pieces OS MCP
- **Deployment:** GitHub Pages (dashboard), local MCP service

---

## 📜 License
MIT License — see [LICENSE](LICENSE) for details.

---

> *“It’s alive… and in perfect harmonic lock.”* — Igor
_
