
## Project Setup

```shell
npx create-next-app@latest ai-companion-app --typescript --eslint --tailwind
src -> No
App Routher -> Yes
customize the default import alias? ->  No 

npx create-next-app@latest ai-companion-app --typescript --eslint --tailwind

# src -> No
# App Routher -> Yes
# customize the default import alias? ->  No 

npx shadcn-ui@latest init

# Ok to proceed? (y) y
# ✔ Would you like to use TypeScript (recommended)? … no / yes
# ✔ Which style would you like to use? › Default
# ✔ Which color would you like to use as base color? › Neutral
# ✔ Where is your global CSS file? … app/globals.css
# ✔ Would you like to use CSS variables for colors? … no / yes
# ✔ Where is your tailwind.config.js located? … tailwind.config.js
# ✔ Configure the import alias for components: … @/components
# ✔ Configure the import alias for utils: … @/lib/utils
# ✔ Are you using React Server Components? … no / yes
# ✔ Write configuration to components.json. Proceed? … yes


# install clerk
# update .env file with clerk keys
# add .env file in .gitignore
npm install @clerk/nextjs
npm i @clerk/themes

# Update layout.tsx and add <ClerkProvider>
# create middleware.tsx

npx shadcn-ui@latest add button

npm i next-themes@latest

npx shadcn-ui@latest add dropdown-menu

npx shadcn-ui@latest add sheet

npx shadcn-ui@latest add input

npx i -D prisma
npm prisma init

npm i dotenv



npm i next-cloudinary

npm i openai

npm i openai-edge

npm i query-string

npm i react-form-stepper

npm i react-hook-form

npm i react-spinners

npm i replicate

npm i stripe

npm i zustand

npm i zod

npm i @hookform/resolvers

npm i @pinecone-database/pinecone

npm i @prisma/client

npm i @radix-ui/react-avatar

npm i @radix-ui/react-dialog

npm i @radix-ui/react-dropdown-menu

npm i @radix-ui/react-label

npm i @radix-ui/react-select

npm i @radix-ui/react-separator
npm i @radix-ui/react-slot
npm i @radix-ui/react-tabs
npm i @radix-ui/react-toast
npm i @radix-ui/react-tooltip
npm i @upstash/ratelimit
npm i @upstash/redis
npm i ai

npm i replicate@0.12.3
npm i langchain

npm i axios

```
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
