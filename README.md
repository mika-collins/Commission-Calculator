# Commission Calculator

A desktop application built with **Electron** and **React** to track and calculate commission-based income.
All data is stored locally (no server required).

---

## Tech Stack

- **Electron** – Desktop application shell
- **React + Vite** – Frontend UI
- **Node.js** – Tooling and runtime
- **Python (planned)** – Local backend + database

---

## Project Structure

```bash
Commission-Calculator/
├── .github/       # GitHub Actions workflows
├── backend/       # Python backend logic
├── electron/      # Electron main process
├── frontend/      # React + Vite frontend
├── package.json   # Root scripts and Electron config
└── README.md
```

---

## Requirements

- **Node.js 20.19+ or 22+** 
Make sure your Node.js version is 20.19+ or 22+ by running `node -v`.
- **npm**
- (Windows users) PowerShell execution policy set to `RemoteSigned`

---

## Setup Instructions

### 1. Clone the repository
```bash
git clone <REPO_URL>
cd Commission-Calculator
```

### 2. Install root dependencies (Electron)
```bash
npm install
```

### 3. Install frontend dependencies
```bash
cd frontend
npm install
cd ..
```

### 4. Run the app (development)
```bash
npm run dev
```
Once the app starts, an Electron window will open showing the "Commission Calculator" header.
