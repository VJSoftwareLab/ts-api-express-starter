# ts-api-express-starter

Starter template for building REST APIs with **TypeScript** and **Express**.

This project provides a clean and scalable foundation to kickstart your Node.js backend development, including basic setup for routing, error handling, linting, and environment configuration.

---

## 🚀 Features

- ⚙️ Express + TypeScript setup  
- ✅ RESTful API example  
- 🧱 Clean and modular folder structure  
- 🐛 Global error handling  
- 🔐 Environment variables via `.env`  
- 🧪 Ready for testing integration  
- 🧹 ESLint + Prettier configured  
- 🏗️ Scripts for development and production  

---

## 📁 Folder Structure

```
src/
│
├── config/        # Environment and configuration files
├── controllers/   # Route handlers
├── routes/        # Express routers
├── services/      # Business logic
├── middlewares/   # Custom middlewares
├── utils/         # Utility functions
├── app.ts         # App initialization
└── server.ts      # Entry point
```

---

## 🛠️ Getting Started

### Prerequisites

- Node.js >= 18  
- Yarn or npm  

### Installation

```bash
git clone https://github.com/VJSoftwareLab/ts-api-express-starter.git
cd ts-api-express-starter
npm install
```

### Running in development

```bash
npm run dev
```

### Building for production

```bash
npm run build
npm start
```

---

## 📄 Available Scripts

- `dev` – Run with ts-node-dev and hot reload  
- `build` – Compile TypeScript to JavaScript  
- `start` – Run compiled app from `/dist`  
- `lint` – Run ESLint  
- `format` – Format code using Prettier  

---

## 🧪 Example Route

Once running, try:

```http
GET http://localhost:3000/api/health
```

Response:

```json
{ "status": "ok" }
```

---

## 📦 Tech Stack

- Node.js  
- Express  
- TypeScript  
- ts-node-dev  
- ESLint & Prettier  
- dotenv  

---

## 🧑‍💻 Author

Developed by [VJSoftwareLab](https://github.com/VJSoftwareLab)

---

## 📝 License

MIT
