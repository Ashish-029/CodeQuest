# CodeQuest 🚀

CodeQuest is an interactive coding-learning platform built with **Next.js**. It lets users go through structured courses, work through chapters, and solve hands-on coding exercises directly in the browser — with authentication, progress tracking, and a built-in code editor.

**🔗 Live Site:** [code-quest-eight-sigma.vercel.app](https://code-quest-eight-sigma.vercel.app/)

---

## ✨ Features

- 📚 Structured courses with chapters and exercises
- 💻 In-browser code editor powered by Sandpack
- 🔐 Secure authentication with Clerk
- 🗄️ PostgreSQL database (via Neon) with Drizzle ORM
- 🎨 Modern UI built with Tailwind CSS and shadcn/ui components
- ⚡ Fast, optimized builds using Next.js 16 with Turbopack

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Framework | [Next.js](https://nextjs.org) |
| Authentication | [Clerk](https://clerk.com) |
| Database | [Neon (PostgreSQL)](https://neon.tech) |
| ORM | [Drizzle ORM](https://orm.drizzle.team) |
| Styling | [Tailwind CSS](https://tailwindcss.com) + [shadcn/ui](https://ui.shadcn.com) |
| Code Editor | [Sandpack](https://sandpack.codesandbox.io) |
| Deployment | [Vercel](https://vercel.com) |

---

## 🚀 Getting Started

Follow these steps to run the project on your own computer.

### 1. Clone the repository

```bash
git clone https://github.com/Ashish-029/CodeQuest.git
cd CodeQuest
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a file named `.env.local` in the project root and add the following:

```env
DATABASE_URL=your_neon_postgres_connection_string
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
```

> 📌 You can get your database URL from [Neon](https://console.neon.tech) and your Clerk keys from the [Clerk Dashboard](https://dashboard.clerk.com/last-active?path=api-keys).

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](https://code-quest-eight-sigma.vercel.app/) in your browser to see the app running.

---

## 📦 Building for Production

```bash
npm run build
npm start
```

Make sure all environment variables from step 3 are also set on your deployment platform (e.g. Vercel) before building — the app will not build without them.

---

## ☁️ Deploying on Vercel

The easiest way to deploy CodeQuest is with [Vercel](https://vercel.com), the platform built by the creators of Next.js:

1. Push your code to GitHub.
2. Import the repository into Vercel.
3. Add the environment variables (`DATABASE_URL`, `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`, `CLERK_SECRET_KEY`) in **Project Settings → Environment Variables**.
4. Click **Deploy**.

For more details, check the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).

---

## 📖 Learn More

- [Next.js Documentation](https://nextjs.org/docs) — learn about Next.js features and API
- [Clerk Documentation](https://clerk.com/docs) — authentication setup and usage
- [Drizzle ORM Documentation](https://orm.drizzle.team/docs/overview) — database schema and queries

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Ashish-029/CodeQuest/issues) if you'd like to contribute.

---

## 📄 License

This project is open source and available for learning and personal use.
