
# Geo-Sentinel: Change Detection & Monitoring

Geo-Sentinel is a web-based geospatial analysis tool designed to detect and simulate changes in land use or vegetation over time using interactive mapping and AI-powered analysis. It integrates interactive drawing tools with satellite change detection simulations and summary analytics.

## 🌐 Features

- 🗺️ **Interactive Map Interface**: Built with Leaflet.js for seamless geospatial interaction.
- 🖊️ **Draw AOI (Area of Interest)**: Define custom regions for change detection.
- 🔍 **Simulate Change Detection**: Run simulations to detect vegetation loss/gain.
- 📊 **AI-Powered Analysis**: Generate natural language summaries using Gemini API.
- ⚠️ **Alert Thresholds**: Get notified when detected changes exceed set thresholds.
- 🧭 **Designed for Accessibility**: Responsive and styled with Tailwind CSS.

## 🛠️ Technologies Used

- HTML, CSS (Tailwind)
- JavaScript (Leaflet.js, Leaflet.draw)
- Gemini API for AI Analysis
- OpenStreetMap tiles for base maps

## 📦 How to Use

1. Open the `Geo-sentinal.html` file in a web browser.
2. Use the drawing tools to mark your Area of Interest (AOI).
3. Adjust the change detection threshold as needed.
4. Run detection to simulate land change and view alerts.
5. Generate an AI-based impact analysis from the detected changes.

## 🧪 Simulated Data

The application uses randomized simulations to imitate real-world vegetation gain/loss based on your selected AOI. No satellite data is used directly.

## ⚠️ Disclaimer

This tool is for educational and demonstrational purposes only. Change detection is simulated and should not be used for decision-making without expert validation.

## 📄 License

MIT License
