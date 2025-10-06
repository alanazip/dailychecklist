# ✅ DailyChecklist

DailyChecklist is a project developed by **FATEC students** as part of a group work.  
It works like a **to-do list / habit tracker**, allowing users to create, manage and check off daily activities with a clean and interactive interface.
---

<img width="1433" height="669" alt="Screenshot at Oct 06 01-12-27" src="https://github.com/user-attachments/assets/55be1fa0-08fd-4c19-b061-5f9f4d1c03d0" />
<img width="1435" height="673" alt="Screenshot at Oct 06 01-12-09" src="https://github.com/user-attachments/assets/584c6518-b508-4d77-87e5-a5e0a7d34aa5" />
<img width="1435" height="669" alt="Screenshot at Oct 06 01-11-41" src="https://github.com/user-attachments/assets/fa5b9357-242e-4ebc-a7aa-26e2231b7dd3" />
<img width="1436" height="659" alt="Screenshot at Oct 06 01-05-51" src="https://github.com/user-attachments/assets/34dbaeda-bf5b-4a0a-8c2a-105c15b4fb02" />

---

## 🎯 Features
- 📌 Add new habits or daily tasks.  
- ✅ Mark habits as completed.  
- 📊 Visualize daily progress through a grid view.  
- 🎨 Modern and responsive UI with **TailwindCSS**.  
- ⚡ Fast frontend built with **Vite + React + TypeScript**.  
- 🗄️ Backend with **Prisma** and Node.js.  
- 🔐 Environment variables configuration via `.env`.

---

## 🛠️ Tech Stack
**Frontend**
- [React](https://reactjs.org/) + [Vite](https://vitejs.dev/)  
- [TypeScript](https://www.typescriptlang.org/)  
- [TailwindCSS](https://tailwindcss.com/)  

**Backend**
- [Node.js](https://nodejs.org/)  
- [Prisma ORM](https://www.prisma.io/)  
- [SQLite / PostgreSQL]  

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/alanazip/dailychecklist.git
cd dailychecklist
````

### 2. Install dependencies

Frontend (`web/`):

```bash
cd web
npm install
```

Backend (`dailychecklist/`):

```bash
cd dailychecklist
npm install
```

### 3. Configure environment variables

Create a `.env` file in both **web** and **dailychecklist** directories with your settings.
Example for backend:

```env
DATABASE_URL="file:./dev.db"
```

### 4. Run database migrations (backend)

```bash
cd dailychecklist
npx prisma migrate dev
```

### 5. Start the applications

Frontend:

```bash
cd web
npm run dev
```

Backend:

```bash
cd dailychecklist
npm run dev
```

---

## 👩‍💻 Authors

Developed as a **group project by FATEC Presidente Prudente students**:

* [Alana Nascimento Prado de Souza](https://github.com/alanazip)



