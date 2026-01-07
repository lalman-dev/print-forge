## 🖨️ Print Forge

  Print Forge is a modern Next.js App Router project built while learning Next.js through a guided course on Scrimba.
  The application showcases a collection of 3D-printable models with category-based navigation, dynamic routes, and server-side data handling.

---

## 🚀 Project Overview

  Print Forge simulates a small marketplace for 3D-printable models.
  Users can:

  - Browse all available models

  - Filter models by category

  - View individual model detail pages

  - Navigate through a clean, component-based UI

  - The project focuses on real-world Next.js fundamentals rather than just UI.

---

## 🧠 What I Learned

  This project helped me gain hands-on experience with:

  - ✅ Next.js App Router

  - ✅ Dynamic routes ([id], [categoryName])

  - ✅ Nested routing and layouts

  - ✅ Server Components & async data fetching

  - ✅ URL-based filtering and navigation

  - ✅ Type-safe data handling with TypeScript

  - ✅ Scalable folder and component structure

---

## ✨ Features

  - 📦 Server-rendered pages for performance

  - 🗂 Category-based filtering

  - 🔗 Dynamic model detail pages

  - 🧩 Reusable UI components

  - 📱 Responsive layout

  - 🧠 Clean separation of data, logic, and UI

---

## 🛠️ Tech Stack

  - Framework: Next.js (App Router)

  - Language: TypeScript

  - Styling: CSS / Global styles

  - Data Source: Local JSON files

  - Concepts: Server Components, Dynamic Routes, Layouts

---

## 📂 Folder Structure

```
app/
├─ 3d-models/
│  ├─ [id]/
│  │  └─ page.tsx              # Model detail page
│  ├─ category/
│  │  └─ [categoryName]/
│  │     └─ page.tsx           # Category filter page
│  ├─ layout.tsx               # Shared layout for models
│  └─ page.tsx                 # All models page
│
├─ about/
│  └─ page.tsx                 # About page
│
├─ components/
│  ├─ CategoriesNav.tsx
│  ├─ ModelCard.tsx
│  ├─ ModelsGrid.tsx
│  ├─ NavBar.tsx
│  ├─ NavLink.tsx
│  └─ Pill.tsx
│
├─ data/
│  ├─ categories.json          # Categories data
│  └─ models.json              # Models data
│
├─ lib/
│  ├─ categories.ts            # Category utilities
│  └─ models.ts                # Model utilities
│
├─ types/
│  └─ types.ts                 # Shared TypeScript types
│
├─ globals.css
├─ layout.tsx                  # Root layout
└─ page.tsx                    # Home page

```

---

## 📌 Credits

This project was built while following a Next.js course on Scrimba.
While the core structure comes from the course, I focused on understanding why each pattern is used and how it applies to real-world applications.

---

## 📈 Why This Project Matters

Print Forge represents my transition from basic React apps to structured, production-style Next.js applications.
It demonstrates my understanding of:

  - Routing architecture

  - Data-driven UI

  - Component reuse

  - Clean project organization

---
## 🔗 Portfolio

👉 https://www.lalman.dev/

