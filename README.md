# TiriVelo Pet Services Web Platform
> The project provides public-facing pages, user registration, dashboards, and additional features. Its primary goal is to promote TiriVelo’s services while allowing customers to sign up, manage their accounts, and easily book pet services online.

## Tech Stack
- **Frontend:** Next.js (App Router), React  
- **Backend / Database:** Supabase (Auth, Database, Storage)  
- **Language / Tools:** TypeScript, Tailwind CSS (optional), ESLint
- **Package Manager (recommended):** pnpm (works with npm/yarn as well)

## Prerequisites
Before running the project, ensure you have:

- Node.js (LTS recommended)  
- pnpm (recommended) or npm / yarn  

Helpful links:  
- [Node.js Downloads](https://nodejs.org/en/download/)  
- [pnpm Installation](https://pnpm.io/installation)  

---

## Setup & Running Locally

1. **Clone the repository**
```bash
git clone https://github.com/TiriVelo-Inc/tirivelo-web.git
cd tirivelo-web
```
Install dependencies

```bash
pnpm install
# or
npm install
# or
yarn install
# or
bun install
```

Set up environment variables

- Create a .env.local file at the project root

Run the development server

```bash
pnpm dev
# or 
npm run dev
# or 
yarn dev
# or
bun run dev
```
Open http://localhost:3000 in your browser.

## Helpful Links

- [Next.js Documentation](https://nextjs.org/docs)  
- [React Documentation](https://react.dev/learn)  