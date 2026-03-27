# 🚀 SENSai

An AI powered full stack web application built using Next.js, Prisma, and PostgreSQL.
SENSai helps users manage resumes, track onboarding, and streamline workflows with a modern UI and scalable backend.

---

## 🌟 Features

* 🔐 Authentication using Clerk
* 📄 Resume management system
* 📊 User onboarding tracking
* ⚡ Fast server side rendering with Next.js
* 🗄️ Database powered by PostgreSQL + Prisma ORM
* 🎯 Clean and responsive UI

---

## 🛠️ Tech Stack

* **Frontend:** Next.js, React
* **Backend:** Next.js API routes
* **Database:** PostgreSQL
* **ORM:** Prisma
* **Auth:** Clerk
* **Styling:** Tailwind CSS

---

## ⚙️ Installation

```bash
git clone https://github.com/ParthGrewal/SENSai.git
cd SENSai
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory and add:

```env
DATABASE_URL="postgresql://postgres:password@localhost:5432/sensai"
```

---

## 🚀 Run Locally

### Development mode:

```bash
npm run dev
```

### Production mode:

```bash
npm run build
npm start
```

---

## 🗄️ Database Setup

```bash
npx prisma generate
npx prisma db push
```

---

## 📂 Project Structure

```
SENSai/
│── app/
│── components/
│── lib/
│── prisma/
│── public/
│── styles/
│── .env
│── package.json
```

---

## ⚠️ Notes

* Ensure PostgreSQL is running locally
* Do NOT upload `.env` file to GitHub
* Use `npm run dev` for development

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Parth Grewal**
GitHub: https://github.com/ParthGrewal
