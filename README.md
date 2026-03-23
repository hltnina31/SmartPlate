# 🍽️ SmartPlate

En fullstack webapplikasjon bygget med PERN stack som gir brukeren tilgang til et personlig dashboard og en KI-drevet oppskriftsgenerator. Brukere kan opprette konto, logge inn, lagre genererte oppskrifter, lage handlelister og planlegge måltider for uken.

---

# 🍽️ SmartPlate

En fullstack webapplikasjon bygget med PERN stack som gir brukeren tilgang til et personlig dashboard og en KI-drevet oppskriftsgenerator. Brukere kan opprette konto, logge inn, lagre genererte oppskrifter, lage handlelister og planlegge måltider for uken.

---

## 📌 Funksjoner

* Brukerautentisering (registrering og innlogging)
* Personlig dashboard
* KI-drevet oppskriftsgenerator (Gemini API)
* Lagring og håndtering av oppskrifter
* Opprettelse av handleliste
* Måltidsplanlegging for uken

---

## 🛠️ Teknologistack

### Fullstack (PERN)

* PostgreSQL (Neon - serverless)
* Express
* React
* Node.js

### Frontend

* React (Vite)
* Tailwind CSS 

### Backend

* Node.js
* Express

### Database

* Neon (serverless PostgreSQL)

### KI / AI

* Gemini API (Google)

---

## 📁 Prosjektstruktur

project-root/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── utils/
│
├── my-app/                 # Frontend (React + Vite)
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── App.tsx
│   │   ├── App.css
│   │   ├── main.tsx
│   │   └── index.css
│   │
│   ├── eslint.config.js
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│   ├── tsconfig.json
│   ├── tsconfig.app.json
│   ├── tsconfig.node.json
│   └── vite.config.ts
│
├── .env
├── .env.example
├── .gitignore
├── LICENSE
└── README.md

---

## ⚙️ Installasjon

### 1. Klon repoet

```bash
git clone https://github.com/ditt-brukernavn/ditt-repo.git
cd ditt-repo
```

### 2. Installer avhengigheter

#### Frontend

```bash
cd frontend
npm install
```

#### Backend

```bash
cd backend
npm install
```

---

## ▶️ Kjør applikasjonen

### Start backend

```bash
cd backend
npm run dev
```

### Start frontend

```bash
cd frontend
npm run dev
```

---

## ☁️ Database (Neon)

Dette prosjektet bruker **Neon (serverless PostgreSQL)**.

1. Opprett en konto på Neon
2. Opprett en database
3. Kopier connection string

---

## 🔐 Miljøvariabler

Opprett en `.env`-fil i backend:

```env
PORT=5000
DATABASE_URL=din_neon_connection_string
GEMINI_API_KEY=din_api_nøkkel
JWT_SECRET=din_hemmelige_nøkkel
```

---

## 📡 API-oversikt

| Metode | Endpoint          | Beskrivelse                  |
| ------ | ----------------- | ---------------------------- |
| POST   | /auth/register    | Opprett bruker               |
| POST   | /auth/login       | Logg inn bruker              |
| POST   | /recipes/generate | Generer oppskrift (KI)       |
| GET    | /recipes          | Hent lagrede oppskrifter     |
| POST   | /shopping-list    | Opprett/oppdater handleliste |
| POST   | /meal-plan        | Opprett måltidsplan          |

---

## 🧠 Hvordan det fungerer

1. Brukeren oppretter konto og logger inn
2. Brukeren får tilgang til et personlig dashboard
3. Oppskrifter genereres ved hjelp av Gemini API
4. Oppskrifter lagres i databasen
5. Brukeren kan lage handleliste og planlegge måltider

---

## 🧪 Videre arbeid

* Forbedre UI/UX
* Filtrering og søk av oppskrifter
* Personlige KI-anbefalinger
* Deployment (Vercel, Railway, Render)
* Deling av oppskrifter mellom brukere

---

## 📄 Lisens

Dette prosjektet er utviklet som en egen personal side prosjekt.

---

## 🙌 Forfatter

Ditt navn
GitHub: https://github.com/hltnina31


---------------------


# 🍽️ Project Name

A fullstack web application built with the PERN stack that provides users with a personalized dashboard and an AI-powered recipe generator. Users can create accounts, log in, save generated recipes, create shopping lists, and plan meals for the week.

---

## 📌 Features

* User authentication (register & login)
* Personalized dashboard
* AI-powered recipe generator (Gemini API)
* Save and manage generated recipes
* Create and manage shopping lists
* Weekly meal planning

---

## 🛠️ Tech Stack

### Fullstack (PERN)

* PostgreSQL (Neon - serverless)
* Express
* React
* Node.js

### Frontend

* React (Vite)
* Tailwind CSS (optional)

### Backend

* Node.js
* Express

### Database

* Neon (serverless PostgreSQL)

### AI

* Gemini API (Google)

---

## 📁 Project Structure

project-root/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── utils/
│
├── my-app/                 # Frontend (React + Vite)
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── App.tsx
│   │   ├── App.css
│   │   ├── main.tsx
│   │   └── index.css
│   │
│   ├── eslint.config.js
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── README.md
│   ├── tsconfig.json
│   ├── tsconfig.app.json
│   ├── tsconfig.node.json
│   └── vite.config.ts
│
├── .env
├── .env.example
├── .gitignore
├── LICENSE
└── README.md

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Install dependencies

#### Frontend

```bash
cd frontend
npm install
```

#### Backend

```bash
cd backend
npm install
```

---

## ▶️ Running the Application

### Start backend

```bash
cd backend
npm run dev
```

### Start frontend

```bash
cd frontend
npm run dev
```

---

## ☁️ Database (Neon)

This project uses **Neon (serverless PostgreSQL)**.

1. Create a Neon account
2. Create a database
3. Copy the connection string

---

## 🔐 Environment Variables

Create a `.env` file in the backend:

```env
PORT=5000
DATABASE_URL=your_neon_connection_string
GEMINI_API_KEY=your_api_key
JWT_SECRET=your_secret_key
```

---

## 📡 API Overview

| Method | Endpoint          | Description                 |
| ------ | ----------------- | --------------------------- |
| POST   | /auth/register    | Register user               |
| POST   | /auth/login       | Login user                  |
| POST   | /recipes/generate | Generate recipe (AI)        |
| GET    | /recipes          | Get saved recipes           |
| POST   | /shopping-list    | Create/update shopping list |
| POST   | /meal-plan        | Create meal plan            |

---

## 🧠 How It Works

1. User registers and logs in
2. User accesses a personalized dashboard
3. User generates recipes using Gemini API
4. Recipes are stored in the database
5. User can manage shopping lists and meal plans

---

## 🧪 Future Improvements

* Improved UI/UX
* Recipe filtering and search
* Personalized AI recommendations
* Deployment (Vercel, Railway, Render)
* Social features (sharing recipes)

---

## 📄 License

This project is developed as a personal side project.

---

## 🙌 Author

Your Name
GitHub: https://github.com/hltnina31
