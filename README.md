# 🌍 Geo-Sentinel Secure

**Geo-Sentinel Secure** is a lightweight geospatial change detection and monitoring tool built with Leaflet.js, Tailwind CSS, and Gemini AI. Users can draw Areas of Interest (AOIs) on a map, simulate land cover changes, and receive AI-generated impact analysis summaries.

---

## 🔗 Live Demo

🟢 Visit the deployed site here:  
👉 [https://geo-sentinel-secure.vercel.app](https://geo-sentinel-secure.vercel.app)

---

## ⚙️ Features

- 🗺️ Draw polygons to define AOIs on the map
- 📊 Simulate vegetation loss/gain with dynamic overlays
- 🧠 Get AI-generated impact analysis using Gemini API
- 📦 Lightweight frontend built with Tailwind + Leaflet
- 🔐 Secure backend protects API key (Node.js + Express)

---

## 🧱 Project Structure

```
geo-sentinel-secure/
├── frontend/
│   └── index.html       # Main web interface
├── backend/
│   ├── server.js        # Node.js API handler
│   ├── package.json     # Backend dependencies
│   └── .env             # (NOT committed) API key storage
```

---

## 🚀 Deployment

### Frontend: Vercel  
Deployed from `frontend/index.html` to:  
➡️ [https://geo-sentinel-secure.vercel.app](https://geo-sentinel-secure.vercel.app)

### Backend: Render  
Deployed from `backend/` to a secured Express server:  
➡️ Exposes `/generate` endpoint to forward prompts to Gemini

---

## 🛡️ Security

This project uses a **Node.js backend** to securely manage the Gemini API key. The key is stored in `.env` and **never exposed to the client**.

Make sure `.env` contains:

```env
GEMINI_API_KEY=your-secret-api-key
```

And is excluded via `.gitignore`.

---

## 🧠 Powered By

- [Leaflet.js](https://leafletjs.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Google Gemini API](https://ai.google.dev/gemini-api)
- [Render](https://render.com/) (Backend Hosting)
- [Vercel](https://vercel.com/) (Frontend Hosting)

---

## 📄 License

MIT License — use freely with attribution.
