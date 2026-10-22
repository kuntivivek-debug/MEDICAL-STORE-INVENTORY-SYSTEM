# Medstock Inventory

A starter MERN stack medical store inventory system with separate frontend and backend applications.

## Structure

```text
medical store inventory system/
|-- backend/
|   |-- src/config/db.js
|   |-- src/models/Medicine.js
|   |-- src/routes/medicineRoutes.js
|   |-- src/server.js
|   |-- .env.example
|   `-- package.json
|-- frontend/
|   |-- src/App.jsx
|   |-- src/main.jsx
|   |-- src/styles.css
|   |-- index.html
|   |-- vite.config.js
|   `-- package.json
|-- package.json
`-- .gitignore
```

## Features in this first slice

- Medicine catalogue with search
- Add medicine form
- Low-stock and expiry indicators
- Delete medicine records
- MongoDB persistence through an Express REST API

## Development roadmap

1. Add update medicine functionality and pagination.
2. Add authentication and roles for admins, pharmacists, and cashiers.
3. Add sales, purchase orders, suppliers, and stock movement history.
4. Add validation, audit logs, reports, and automated tests.
5. Add deployment configuration and production secrets.

See the execution steps in the project handoff for local setup.
