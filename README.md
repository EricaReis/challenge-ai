# 🛰️ **Webhook Inspector**

[![Node.js](https://img.shields.io/badge/Node.js-LTS-green?logo=node.js)](https://nodejs.org/)
[![Fastify](https://img.shields.io/badge/Backend-Fastify-blue?logo=fastify)](https://fastify.dev/)
[![React](https://img.shields.io/badge/Frontend-React-61DAFB?logo=react)](https://react.dev/)
[![Postgres](https://img.shields.io/badge/Database-Postgres-336791?logo=postgresql)](https://www.postgresql.org/)
[![Google AI](https://img.shields.io/badge/AI-Google%20Generative%20AI-4285F4?logo=google)](https://cloud.google.com/generative-ai)

---

### 🧠 Full-stack AI-powered tool for capturing, inspecting, and generating **TypeScript webhook handlers**.

Webhook Inspector lets you:
- 🕵️ Capture and visualize webhook payloads in real time  
- 🔍 Inspect data and metadata easily  
- 🤖 Generate **TypeScript handlers automatically** using **Google Generative AI**

---

## ⚙️ **Tech Stack**

| Layer | Stack |
|:------|:------|
| **Backend** | [Fastify](https://fastify.dev/), [Drizzle ORM](https://orm.drizzle.team/), **PostgreSQL** |
| **Frontend** | [React](https://react.dev/), [Vite](https://vitejs.dev/) |
| **AI Integration** | [Google Generative AI](https://cloud.google.com/generative-ai) |
| **Tooling** | Node.js, pnpm |

---

## ⚙️ **Quick Setup Guide**
Here is a consolidated sequence of commands you can use to install dependencies, set up the database, and start both the API and the Frontend (assuming you start from the project root and open a second terminal when instructed).

#### Setup .env file

Create a file named .env inside the api/ folder with the following content:

```shell
DATABASE_URL=<your_postgres_connection_string>
GOOGLE_GENERATIVE_AI_API_KEY=<your_google_gen_ai_key>
```

#### 1. Install all project packages
```shell
pnpm install
```

#### 2. Navigate to API folder
```shell
cd api
```

#### 3. Apply database migrations and seed data
#### *NOTE: Ensure your .env file is set up with DATABASE_URL first!*
```shell
pnpm run db:migrate
pnpm run db:seed
```

#### 4. Start the API (Backend)
```shell
pnpm run dev
```

#### --- OPEN A NEW TERMINAL FOR THE NEXT STEPS ---

#### 5. Navigate to Frontend folder in the new terminal
```shell
cd web
```

#### 6. Start the Frontend (Web)
```shell
pnpm run dev
```

✅ Access the App
Open your browser at: http://localhost:5173

---

## 👩 **Developer**

<p align="center"> <img src="https://avatars.githubusercontent.com/u/43284359?s=460&u=d0283f2331fb2e66792ff944985f576defbcfb77&v=4" width="120" style="border-radius: 50%;" alt="Érica Reis avatar"/> </p> <p align="center"> <b>Érica Reis</b> <br/> <a href="mailto:ericabeatrizdosreis@gmail.com">ericabeatrizdosreis@gmail.com</a> </p> <p align="center"> 💡 Full-stack Developer | 🚀 Passionate about web technologies & AI </p>


