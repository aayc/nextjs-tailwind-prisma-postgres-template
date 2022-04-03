# Get started

This template has Next.js, Tailwindcss, and Prisma ORM for a full stack web application.

## Installation

Clone this repository and install dependencies:

```
git clone git@github.com:aayc/nextjs-tailwind-prisma-postgres.git
yarn install
```

Create DB env with credentials to connect to your database:

```
cd <this-template-path>
vim .env
```

Your env may look like the following:

```
# Environment variables declared in this file are automatically made available to Prisma.
# See the documentation for more detail: https://pris.ly/d/prisma-schema#accessing-environment-variables-from-the-schema

# Prisma supports the native connection string format for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB (Preview) and CockroachDB (Preview).
# See the documentation for all the connection string options: https://pris.ly/d/connection-strings

DATABASE_URL="postgresql://johndoe:randompassword@localhost:5432/mydb?schema=public"
```
