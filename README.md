# Trendify – Full-Stack E-commerce Platform Built with Next.js

**Trendify** is a modern, full-featured e-commerce web application built with **Next.js 15**, **React 19**, and **TypeScript**. Designed to offer a seamless shopping experience, Prostore includes robust features like payment integration, user authentication, admin dashboards, and product reviews — all styled with a clean, responsive UI.

This project demonstrates the power of combining modern full-stack tools and best practices to build a scalable and production-ready web application.

---

## Tech Stack

### Frontend

- **Next.js 15**
- **React 19**
- **TypeScript**
- **Tailwind CSS** + **ShadCN UI**
- **Recharts** – Data Visualization
- **React Hook Form** – Form Handling
- **Zod** – Validation
- **Uploadthing** – File Uploads

### Backend

- **Prisma** – ORM
- **PostgreSQL** – Relational Database
- **NextAuth** – Authentication
- **Stripe** & **PayPal APIs** – Payment Integration

### Tooling & Testing

- **ESLint** – Code Linting
- **Jest** – Unit Testing

---

## Features

- Secure User Authentication with NextAuth
- Full Shopping Cart & Checkout Experience
- Payment Integration with Stripe & PayPal
- Email Receipt Generation
- Product Ratings and Reviews
- Admin Dashboard with Data Visualization (Recharts)
- Product Image & File Uploads
- Responsive UI with Accessible Design (Tailwind + ShadCN)
- End-to-End Form Validation and Error Handling (Zod + RHF)

---

## Project Structure

- /app - Next.js app directory
- /components - Reusable UI components
- /lib - Utilities and helpers
- /prisma - Prisma schema & migrations
- /public - Static assets
- /styles - Tailwind and global styles
- /tests - Unit tests

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
