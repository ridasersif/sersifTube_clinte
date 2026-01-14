# SersifTube Client

Frontend UI for SersifTube YouTube downloader. Built with React, Vite, and TailwindCSS.

## 🚀 Quick Start

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Configure environment:**
   ```bash
   cp .env.example .env
   ```
   Edit `.env` and set:
   - `VITE_API_URL`: Backend server URL (e.g., `http://localhost:5000`)

3. **Start development server:**
   ```bash
   npm run dev
   ```

Frontend runs on `http://localhost:3000`

## 📦 Deployment (Vercel)

This frontend is ready for deployment on **Vercel**.

### Steps:

1. **Push to GitHub:**
   - Ensure this `client` folder is in a GitHub repository.

2. **Deploy on Vercel:**
   - Go to [Vercel.com](https://vercel.com)
   - Click "Add New Project" → "Import from GitHub"
   - Select your frontend repository

3. **Configure Settings:**
   - **Framework Preset**: Vite
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`

4. **Configure Environment Variables:**
   Add this variable in Vercel:
   - `VITE_API_URL`: Your deployed backend URL (e.g., `https://your-api.up.railway.app`)

5. **Deploy!**

## 🛠️ Tech Stack

- **Framework**: React 19 + Vite
- **Styling**: TailwindCSS
- **Real-time**: Socket.IO Client
- **Icons**: Lucide React

## 📄 License

MIT
