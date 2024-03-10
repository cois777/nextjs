# NextJS Documentation

## Features of NextJS
* Hot Code Reloading: It automatically reloads the application when changes in the code get saved.
* Automatic Code Splitting: By this feature, every import in the code get bundled and served with each page. It means that unnecessary code never get loaded on the page.
* Ecosystem Compatibility: Compatible with JavaScript, Node and react.
* Server Rendering: Easily render react component on server before sending HTML to client.
* Styled-JSX: Styled-JSX allows you to write CSS directly inside JavaScript code.

## Prisma
Prisma is a next-generation ORM that can be used to access a database in Node.js and TypeScript applications. In this guide, you'll learn how to implement a sample fullstack blogging application using the following technologies:
* Next.js as the React framework
* Next.js API Routes for server-side API routes as the backend
* Prisma as the ORM for migrations and database access
* Vercel Postgres as the database
* NextAuth.js for authentication via GitHub (OAuth)
* TypeScript as the programming language
* Vercel for deployment

# Steps
## start from an existing repo
```
npx create-next-app --example https://github.com/Yazdun/next-fcc-familyguy/tree/starter nextjs-famguy
```

## Dependencies
* @emotion/react
* @emotion/style
* @mui/material
* @mui/system
* @mui/x-data-grid
* @next-auth/prisma-adapter
* @prisma/client
* @radix-ui/react-dropdown-menu
* @radix-ui/react-scroll-area
* @radix-ui/react-tabs
* @total-typescript/ts-reset
* @upstash/ratelimit
* @upstash/redis
* class-variance-authority
* clsx
* date-fns
* framer-motion
* lodash
* lucide-react
* nanoid
* next-auth
* next-themes
* openai
* prism-react-renderer
* prisma
* react-hot-toast
* sharp
* simplebar-react
* tailwind-merge
* zod

install with yarm:
```
yarn add @emotion/react @emotion/style @mui/material @mui/system @mui/x-data-grid @next-auth/prisma-adapter @prisma/client @radix-ui/react-dropdown-menu @radix-ui/react-scroll-area @radix-ui/react-tabs @total-typescript/ts-reset @upstash/ratelimit @upstash/redis class-variance-authority clsx date-fns framer-motion lodash lucide-react nanoid next-auth next-themes openai prism-react-renderer prisma react-hot-toast sharp simplebar-react tailwind-merge zod
```