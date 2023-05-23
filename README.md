This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

-   [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
-   [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Intro to NextJs

-   Create `app` folder and add a `layout.tsx` and `page.tsx` file. These will be rendered when the user visits the root of your application.

-   Create the `public` folder. You can optionally create a `public` folder to store static assets such as images, fonts, etc. Files inside `public` directory can then be referenced by your code starting from the base URL `/`.

## Project Structure

-   `next.config.js` => Configuration file for Nextjs

-   `middleware.ts` => Nextjs request middleware

-   `.env` => Environment variables

-   `.env.local` => Local environment variables

-   `.env.production` => Production environment variables

-   `.next-env.d.ts` => TypeScript declaration file for Nextjs

-   `package.json` => Project dependencies and scripts

## Top-level folders

-   `app` => App Router

-   `pages` => Pages Router

-   `public` => Static assets to be served

-   `src` => Optional application source folder
