# Next.js Official Learning Tutorial
Link: [https://nextjs.org/learn/]
Vercel: [https://nextjs-dashboard-six-tau-86.vercel.app/]

## Progress

[https://nextjs.org/learn/dashboard-app/adding-metadata]

## Packages

```bash
pnpm i @vercel/postgres
// To resolve compatibility issue with PPR
pnpm i next@canary
// Debouncing
pnpm i use-debounce
// NextAuth.js
pnpm i next-auth@beta
// Generate a secret key for your application. This key is used to encrypt cookies, ensuring the security of user sessions.
openssl rand -base64 32
```

## Next.js starter templates and themes
[https://vercel.com/templates/next.js]

## ESLint

Optionally, if you would like to try this out, add next lint as a script in your package.json file:

```bash
"scripts": {
    "build": "next build",
    "dev": "next dev",
    "start": "next start",
    "lint": "next lint"
},
```
Then run pnpm lint in your terminal:

```bash
pnpm lint
```

## Neon Database

Log in with GitHub account.

## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
