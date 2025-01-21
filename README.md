
Only test cards


sidenote: Both of the stripe api keys are test mode keys. (Ashish 17.01.2025 : AT time 7:00 pm)

Only test card works with test keys.


Only this card works : 4242424242424242
For live cards, live API required

🤩Please dont change the things above🤩






# Prostore

A full featured Ecommerce website built with Next.js, TypeScript, PostgreSQL and Prisma.

<img src="/public/images/screen.png" alt="Next.js Ecommerce" />

This project is from my **Next.js Ecommerce course**

- Traversy Media: https://www.traversymedia.com/nextjs-ecommerce
- Udemy: https://www.udemy.com/course/nextjs-ecommerce-course

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
- Much more

## Usage

### Install Dependencies

```bash
npm install
```

Note: Some dependencies may have not yet been upadated to support React 19. If you get any errors about depencency compatability, run the following:

```bash
npm install --legacy-peer-deps
```

### Environment Variables

Rename the `.example-env` file to `.env` and add the following

#### PostgreSQL Database URL

Sign up for a free PostgreSQL database through Vercel. Log into Vercel and click on "Storage" and create a new Postgres database. Then add the URL.

**Example:**

```
DATABASE_URL="postgresql://username:password@host:port/dbname"
```
```
ashish vercel
DATABASE_URL=postgres://neondb_owner:Z4NUGVTxC8tl@ep-young-union-a2io64yz-pooler.eu-central-1.aws.neon.tech/neondb?sslmode=require
``` 


#### Next Auth Secret

Generate a secret with the following command and add it to your `.env`:

```bash
openssl rand -base64 32
```

**Example:**

```
NEXTAUTH_SECRET="xmVpackzg9sdkEPzJsdGse3dskUY+4ni2quxvoK6Go="
```

#### PayPal Client ID and Secret

Create a PayPal developer account and create a new app to get the client ID and secret.

**Example:**

```
PAYPAL_CLIENT_ID="AeFIdonfA_dW_ncys8G4LiECWBI9442IT_kRV15crlmMApC6zpb5Nsd7zlxj7UWJ5FRZtx"
PAYPAL_APP_SECRET="REdG53DEeX_ShoPawzM4vQHCYy0a554G3xXmzSxFCDcSofBBTq9VRqjs6xsNVBcbjqz--HiiGoiV"
```

#### Stripe Publishable and Secret Key

Create a Stripe account and get the publishable and secret key.

**Example:**

```
STRIPE_SECRET_KEY="sk_test_51QIr0IG87GyTererxmXxEeqV6wuzbmC0TpkRzabxqy3P4BpzpzDqnQaC1lZhmYg6IfNarnvpnbjjw5dsBq4afd0FXkeDriR"
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY="pk_test_51QIr0Ids7GyT6H7X6R5GoEA68lYDcbcC94VU0U02SMkrrrYZT2CgSMZ1h22udb5Rg1AuonXyjmAQZESLLj100W3VGVwze"
```

#### Uploadthing Settings

Sign up for an account at https://uploadthing.com/ and get the token, secret and app ID.

**Example:**

```
UPLOADTHING_TOKEN='tyJhcGlLZXkiOiJza19saXZlXzQ4YTE2ZjhiMDE5YmFiOgrgOWQ4MmYxMGQxZGU2NTM3YzlkZGI3YjNiZDk3MmRhNGZmNGMwMmJlOWI2Y2Q0N2UiLCJhcHBJZCI6InRyejZ2NHczNzUiLCJyZWdpb25zIjpbInNlYTEiXX0='
UPLOADTHIUG_SECRET='gg'
UPLOADTHING_APPID='trz6vd475'
```

#### Resend API Key

Sign up for an account at https://resend.com  and get the API key.

**Example:**

```
RESEND_API_KEY="re_ZnhUfrjR_QD2cDqdee3iYCrkfvPYFCYiXm"
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

## Demo

I am not sure how long I will have this demo up but you can view it here:

https://prostore-one.vercel.app/

## Note On Vercel Deployment For Hobby Plan

In order to fit within the limitations of the Vercel hobby plan, we removed the **bcrypt-ts-edge** package and added custom encryption. Now the full project can be deployed to the Hobby plan.

## License

MIT License

Copyright (c) [2025] [Traversy Media]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall
# prostore-main





# Screenshots
![1](https://github.com/user-attachments/assets/55618409-5423-4454-8bff-cd2cdb88009c)
![2](https://github.com/user-attachments/assets/4989b141-52bb-431f-a480-0194799711aa)
![22](https://github.com/user-attachments/assets/4648c23d-c975-4a84-ad54-29eef1752f7e)
![222](https://github.com/user-attachments/assets/7c48187a-a4ef-41aa-8e72-80bfac85ce99)
![3](https://github.com/user-attachments/assets/1161d087-9fc2-47e6-a86d-8ddd79a7b7a3)
![333](https://github.com/user-attachments/assets/871111dc-f311-4dbd-b1bd-36be2ed429dc)pa
![payment](https://github.com/user-attachments/assets/a16a76b3-b4b2-4656-b5ef-39638eb9c698)

![4](https://github.com/user-attachments/assets/732d355d-df4e-463a-94b2-417f515a97d1)
![5](https://github.com/user-attachments/assets/1f80b908-7e41-4605-bdd2-034d61c3b458)
![6](https://github.com/user-attachments/assets/d4241a7c-75d3-4e6f-ada4-87ff058b1b5c)

![7](https://github.com/user-attachments/assets/51c12a6e-09e9-44d9-93d2-7a01b090c05e)

![Screenshot 2025-01-12 at 9 40 10 PM](https://github.com/user-attachments/assets/1b9fac5a-37e0-4edb-963d-d4a687d70cb1)



# prostore
