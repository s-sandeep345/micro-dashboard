# Micro-Frontend Dashboard

React + TypeScript + Vite + Module Federation dashboard.

Apps: shell 5173, auth 5174, dashboard 5175, users 5176, analytics 5177, notifications 5178.

Demo login: admin@example.com / password123

Run each app in a separate terminal:
```bash
cd auth && npm install && npm run dev
cd dashboard && npm install && npm run dev
cd users && npm install && npm run dev
cd analytics && npm install && npm run dev
cd notifications && npm install && npm run dev
cd shell && npm install && npm run dev
```
Then open http://localhost:5173.

Each remote exposes a federated module and the shell lazy-loads it. Mock service/data layers are used so no backend is required.
