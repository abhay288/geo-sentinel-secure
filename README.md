# 🌍 Geo-Sentinel Secure

**Geo-Sentinel Secure** is a lightweight geospatial change detection and monitoring tool built with Leaflet.js, Tailwind CSS, and Gemini AI. Users can draw Areas of Interest (AOIs) on a map, simulate land cover changes, and receive AI-generated impact analysis summaries.

---

## 🔗 Live Demo

🟢 Visit the deployed site here:  
👉 [https://geo-sentinel-secure.vercel.app](https://geo-sentinel-secure.vercel.app)

---

## ⚙️ Features

- 🗺️ **Interactive Map Interface**: Built with Leaflet.js for seamless geospatial interaction.
- 🖊️ **Draw AOI (Area of Interest)**: Define custom regions for change detection.
- 🔍 **Simulate Change Detection**: Run simulations to detect vegetation loss/gain.
- 📊 **AI-Powered Analysis**: Generate natural language summaries using Gemini API.
- ⚠️ **Alert Thresholds**: Get notified when detected changes exceed set thresholds.
- 🧭 **Designed for Accessibility**: Responsive and styled with Tailwind CSS.

---
## 📦 How to Use

1. Open the website using above given link .
2. Use the drawing tools to mark your Area of Interest (AOI).
3. Adjust the change detection threshold as needed.
4. Run detection to simulate land change and view alerts.
5. Generate an AI-based impact analysis from the detected changes.


## 🛠️ Technologies Used

- HTML, CSS (Tailwind)
- JavaScript (Leaflet.js, Leaflet.draw)
- Gemini API for AI Analysis
- OpenStreetMap tiles for base maps

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

## 🧪 Simulated Data

The application uses randomized simulations to imitate real-world vegetation gain/loss based on your selected AOI. No satellite data is used directly.

## ⚠️ Disclaimer

This tool is for educational and demonstrational purposes only. Change detection is simulated and should not be used for decision-making without expert validation.

## 🧠 Powered By

- [Leaflet.js](https://leafletjs.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Google Gemini API](https://ai.google.dev/gemini-api)
- [Render](https://render.com/) (Backend Hosting)
- [Vercel](https://vercel.com/) (Frontend Hosting)

---

## 📄 License

❌ Not Download This Directly Take Permission From me then Use it with Credit.
Author - Abhay Kushwaha 😎
