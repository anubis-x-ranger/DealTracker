📊 DealTracker

A simple CRUD web app for tracking private equity deals. Built with Express.js, PostgreSQL, and AG Grid (React).

This project is part of a weekend build challenge to learn Postgres with Express.js while creating portfolio-worthy finance tools.
🚀 Features

Add, view, update, and delete deals.

Each deal includes:

Company Name

Deal Size

Date

Interactive frontend table with AG Grid.

Backend API built with Express.js.

Database powered by PostgreSQL.

Deployed on Render (backend + DB) and Vercel (frontend).

🏗️ Tech Stack

Frontend: React, RSBuild, AG Grid, TailwindCSS

Backend: Node.js, Express.js

Database: PostgreSQL (Render free tier)

Deployment: Render (backend + DB), Vercel (frontend)

Testing: Jest (basic API tests)

CI/CD: GitHub Actions

deal-tracker/
│── backend/                 # Express.js + PostgreSQL backend
│   ├── src/
│   │   ├── index.js         # App entry
│   │   ├── routes/          # API routes
│   │   ├── controllers/     # Business logic
│   │   ├── models/          # SQL queries
│   │   └── db/              # Schema + DB connection
│   └── tests/               # Jest tests
│
│── frontend/                # RSBuild + React + AG Grid frontend
│   ├── src/components/      # DealGrid + DealForm
│   └── services/            # Axios API wrapper
│
│── docs/                    # Documentation + writeups
│── README.md
└── .github/workflows/       # CI/CD pipelines
