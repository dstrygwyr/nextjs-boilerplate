# 🧪 Next.js Frontend Boilerplate

A modern and minimal **Next.js** + **TypeScript** starter template packed with:

- ⚡️ [Next.js](https://nextjs.org/) – Full-stack React framework
- 🎨 [Tailwind CSS](https://tailwindcss.com/) – Utility-first styling
- 🧩 [ShadCN UI](https://ui.shadcn.dev/) – Accessible, customizable components
- 🪶 [Lucide React](https://lucide.dev/) – Beautiful icons
- 💡 [TypeScript](https://www.typescriptlang.org/) – Static type safety
- 🧼 [Biomejs](https://biomejs.dev/) – Code linting & formatting

---

## 📦 Features

- ⚛️ Built with App Router (`app/`) support
- 🎨 Themeable UI with ShadCN and Tailwind
- 🌙 Dark mode support
- 🧩 Reusable components
- 🪶 Lucide icon system integration
- 💅 Opinionated code style (Biemojs)
- 🧪 Optimized developer experience

---

## 🧱 Project Structure

```
src/
├── app/               # App router pages & layout
│   ├── layout.tsx     # Root layout
│   └── page.tsx       # Home page
├── components/        # UI components (e.g. buttons, inputs)
├── lib/               # Utilities (e.g. cn helper, constants)
```

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
npx create-next-app@latest your-app-name -e https://github.com/dstrygwyr/your-repo
```

Or clone manually:

```bash
git clone https://github.com/dstrygwyr/nextjs-boilerplate.git <your-project>
cd <your-project>
pnpm install # or npm install / yarn install
```

### 2. Run the dev server

```bash
pnpm dev
```

---

## 🛠️ Setup & Configuration

### Install ShadCN UI

```bash
npx shadcn-ui@latest init
```

Follow the prompts to configure your project (select \`app/\`, \`tailwind\`, \`tsx\`, etc.)

### Install Lucide Icons

```bash
pnpm add lucide-react
```

Then use any icon like:

```tsx
import { SearchIcon } from "lucide-react";

<SearchIcon className="w-4 h-4" />
```

---

## ✅ Linting & Formatting

```bash
pnpm lint       # Run ESLint
pnpm format     # Run Prettier
```

---

## 📄 License

MIT — feel free to use and modify for personal or commercial projects.

---
