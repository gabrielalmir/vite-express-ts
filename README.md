# Vite + Express + TypeScript

This project is a template for building a web application using Vite, React, Express, and TypeScript.

## Project Structure

```
vite-express-ts/
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── README.md
├── src/
│   ├── backend/
│   │   └── server.ts
│   ├── frontend/
│   │   ├── App.css
│   │   ├── App.tsx
│   │   ├── assets/
│   │   ├── index.css
│   │   ├── main.tsx
│   │   └── vite-env.d.ts
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
  ```sh
  git clone https://github.com/gabrielalmir/vite-express-ts.git
  cd vite-express-ts
  ```

2. Install dependencies:
  ```sh
  npm install
  # or
  yarn install
  ```

### Running the Application

To start both the frontend and backend servers in development mode, run:
```sh
npm run dev
# or
yarn dev
```

The frontend will be available at `http://localhost:3000` and the backend at `http://localhost:3000/api`.

### Building for Production

To build the project for production, run:
```sh
npm run build
# or
yarn build
```

### Linting

To lint the project, run:
```sh
npm run lint
# or
yarn lint
```
