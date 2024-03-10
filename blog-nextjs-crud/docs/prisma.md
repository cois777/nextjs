# Prisma

[Prisma Site](https://www.prisma.io/docs/orm/overview/databases/sqlite)

## Prisma
Prisma is a next-generation ORM that can be used to access a database in Node.js and TypeScript applications. In this guide, you'll learn how to implement a sample fullstack blogging application using the following technologies:
* Next.js as the React framework
* Next.js API Routes for server-side API routes as the backend
* Prisma as the ORM for migrations and database access
* Vercel Postgres as the database
* NextAuth.js for authentication via GitHub (OAuth)
* TypeScript as the programming language
* Vercel for deployment

## Commands
Install
```
npm install prisma --save-dev
```
Next, we initialize Prisma:
```
npx prisma init
```
Update your schema.prisma file so it looks like this:
```
// This is your Prisma schema file,
// learn more about it in the docs: https://pris.ly/d/prisma-schema

// Looking for ways to speed up your queries, or scale easily with your serverless or edge functions?
// Try Prisma Accelerate: https://pris.ly/cli/accelerate-init

generator client {
  provider = "prisma-client-js"
}

datasource db {
  provider = "sqlite"
  url      = env("DATABASE_URL")
}

// defines a Post model
model Post {
  id          String    @id @default(cuid())
  title       String
  content     String
  createdAt   DateTime  @default(now())
  updatedAt   DateTime  @updatedAt
}
```
Create DB
```
npx prisma db push
```