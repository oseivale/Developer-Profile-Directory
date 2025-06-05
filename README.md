# Developer-Profile-Directory

# 💼 DevLink – Developer Profile Directory

Welcome to **DevLink**, a fun and beginner-friendly frontend project built with **Next.js**, **TypeScript**, and **ShadCN UI**.

This project is designed to help you apply your skills in React, TypeScript, and modern UI practices, while also getting familiar with how to build a real-world application using Next.js and reusable component design.

---

## 🚀 Project Overview

**DevLink** is a web-based directory where developers can:
- Submit a profile with their name, role, tech stack, and social links.
- View a list of other developers in a searchable card layout.
- Click on a developer to view a detailed profile (optional).

---

## 🧰 Tech Stack

- [Next.js](https://nextjs.org/) – Routing & framework
- [TypeScript](https://www.typescriptlang.org/) – Type-safe code
- [ShadCN UI](https://ui.shadcn.com/) – Pre-built components
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first styling
- [React](https://reactjs.org/) – Component-based UI

> Optional enhancements:
> - [React Hook Form](https://react-hook-form.com/) + [Zod](https://github.com/colinhacks/zod) for form validation
> - [Framer Motion](https://www.framer.com/motion/) for animations
> - LocalStorage or Supabase/Firebase to simulate backend persistence

---

## 📂 Project Structure (Suggested)

├── app/
│   ├── page.tsx (Home)
│   ├── directory/
│   │   └── page.tsx
│   ├── add-profile/
│   │   └── page.tsx
│   └── profile/[id]/
│       └── page.tsx (Optional)
├── components/
│   ├── developer-card.tsx
│   ├── profile-form.tsx
│   └── header.tsx
├── types/
│   └── index.ts
├── utils/
│   └── localStorage.ts (or mock API functions)
└── README.md

---

## 🎯 Features

### ✅ Core Requirements

- [ ] **Homepage** with welcome text and CTA buttons.
- [ ] **Directory page** that lists all developer profiles in card format.
- [ ] **Add Profile page** with form inputs:
  - Full Name
  - Role / Title
  - Bio
  - Tech Stack (multi-select or tag input)
  - GitHub / LinkedIn / Website links
- [ ] **DeveloperCard** component for reusable display of profile info.
- [ ] Store and display profiles using `useState` (or optionally LocalStorage).

### ⚙️ Bonus Features (Stretch Goals)

- [ ] Profile detail page (`/profile/:id`)
- [ ] Search or filter by name or tech stack
- [ ] Dark mode toggle with ShadCN
- [ ] Form validation (Zod + RHF)
- [ ] Smooth animations (Framer Motion)
- [ ] Host on Vercel

---

## 📅 Suggested Timeline (1 Week Plan)

| Day       | Goal                                                      |
|-----------|-----------------------------------------------------------|
| **Day 1** | Setup Next.js + ShadCN + Tailwind + TS. Create homepage.  |
| **Day 2** | Create and style Directory page with static cards.        |
| **Day 3** | Build reusable `developer-card` component.                 |
| **Day 4** | Create Add Profile page with form UI.                     |
| **Day 5** | Handle form state and add profile to directory.           |
| **Day 6** | Add search/filter. Refine layout and styling.             |
| **Day 7** | Polish UI. Add optional features. Refactor & deploy.      |

---

## 🛠️ Getting Started

### Prerequisites

- Node.js ≥ 18
- pnpm or yarn (preferred over npm)
- Git

### Setup Instructions

```bash
# Clone the repo
git clone https://github.com/your-username/devlink.git
cd devlink

# Install dependencies
pnpm install

# Run the dev server
pnpm dev

Visit http://localhost:3000 to see the app locally.

Learning Objectives
	•	Practice reusable component design
	•	Apply form handling and validation
	•	Understand routing and file structure in Next.js
	•	Use TypeScript interfaces to model and type data
	•	Build responsive layouts with Tailwind & ShadCN

Final Tips
	•	Commit often and write descriptive messages.
	•	Focus on one feature at a time.
	•	Don’t be afraid to Google or ask for help.
	•	Have fun and make it your own!
