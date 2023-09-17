# Ecommerce Store admin panel

Made using Next.js, Typescript & PrismaDB

Store admin and configuration part of the ecommerce fullstack dashboard app

Ecommerce store available [here](https://github.com/botfinski/ecommerce-store)

To run create .env file

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
CLERK_SECRET_KEY
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME
STRIPE_API_KEY
FRONTEND_STORE_URL=http://localhost:3001
STRIPE_WEBHOOK_SECRET
```

then run

```bash
npm install
npm run dev
```
