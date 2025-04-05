Preview https://prostore-smoky.vercel.app 


# Prostore

A full featured e-commerce website built with Next.js, TypeScript, PostgreSQL and Prisma.

<img src="/public/images/screen.png" alt="Next.js Ecommerce" />


## Features

- Next Auth authentication
- Admin area with stats & chart using Recharts
- Order, product and user management
- User area with profile and orders
- Stripe API integration
- PayPal integration
- Cash on delivery option
- Interactive checkout process
- Featured products with banners
- Multiple images using Uploadthing
- Ratings & reviews system
- Search form (customer & admin)
- Sorting, filtering & pagination
- Dark/Light mode

## Usage - Steps to run the project

### Install Dependencies

```bash
npm install
```



```bash
npm install --legacy-peer-deps
```


### Run

```bash

# Run in development mode
npm run dev

# Build for production
npm run build

# Run in production mode
npm start

# Export static site
npm run export
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Prisma Studio

To open Prisma Studio, run the following command:

```bash
npx prisma studio
```

## Seed Database

To seed the database with sample data, run the following command:

```bash
npx tsx ./db/seed
```
