# 🌿 ecoSort — Frontend

User interface for the ecoSort waste-sorting application. Built with **React** and **TypeScript**.

---

## 📋 Table of Contents

- [About](#about)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Running the App](#running-the-app)
- [Building for Production](#building-for-production)
- [Related Repository](#related-repository)

---

## About

ecoSort is a web application that helps users identify and sort waste correctly — recycling, composting, or landfill — for a better environment. This repository contains the frontend interface that communicates with the ecoSort backend API.

---

## Tech Stack

- **Language:** TypeScript
- **Framework:** React
- **Styling:** TailwindCSS
- **Dashboard Template:** [TailAdmin React (Free)](https://tailadmin.com/) — MIT License

---

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mohamed-Adam-Jemal/ecoSort-frontend.git
   cd ecoSort-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables** (see section below)

---

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
VITE_API_BASE_URL=http://127.0.0.1:8000
```

> ⚠️ Never commit your `.env` file. It is already listed in `.gitignore`.

---

## Running the App

```bash
npm run dev
# or
yarn dev
```

The app will be available at `http://localhost:5173/`.

Make sure the backend server is also running at the URL defined in `VITE_API_BASE_URL`.

---

## Building for Production

```bash
npm run build
# or
yarn build
```

Output will be in the `dist/` folder, ready to be served by any static hosting provider (Vercel, Netlify, etc.).

---

## Credits

The dashboard UI is based on **[TailAdmin React (Free)](https://github.com/TailAdmin/free-react-tailwind-admin-dashboard)**, an open-source admin dashboard template built with React and Tailwind CSS.

- 🌐 Website: [tailadmin.com](https://tailadmin.com/)
- 📄 License: [MIT](https://github.com/TailAdmin/free-react-tailwind-admin-dashboard/blob/main/LICENSE)
- 🖌️ Demo: [free-react-demo.tailadmin.com](https://free-react-demo.tailadmin.com/)

> Modifications were made to adapt the template to the ecoSort application.

---

## Related Repository

- ⚙️ **Backend:** [ecoSort-backend](https://github.com/Mohamed-Adam-Jemal/ecoSort-backend) — Django REST API (Python)

---

## License

This project is licensed under the [MIT License](LICENSE).
