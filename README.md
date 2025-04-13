This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

**Set Up Environment Variables**

Create a new file named `.env` with the following content:

```env
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=

NEXT_PUBLIC_API_ENDPOINT=
NEXT_PUBLIC_PROD_API_ENDPOINT=

DATABASE_URL=

UPSTASH_REDIS_URL=
UPSTASH_REDIS_TOKEN=

AUTH_SECRET=

QSTASH_URL=
QSTASH_TOKEN=

RESEND_TOKEN=
EMAIL_DOMAIN=
```

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

## Features

Features include:
* **Advanced Functionalities**: Caching, rate-limiting, DDoS protection, and custom notifications.
* **Database Management**: Postgres with Neon for scalable and collaborative database handling.
* **Real-time Media Processing**: ImageKit for image and video optimization and transformations.
* **Efficient Caching**: Upstash Redis for caching, workflows, and triggers.
* **Database ORM**: Drizzle ORM for simplified and efficient database interactions.
* **Modern UI/UX**: Built with TailwindCSS, ShadCN, and other cutting-edge tools.
* **Technology Stack**: Next.js with TypeScript for scalable development, and NextAuth for robust authentication.
* **Seamless Email Handling**: Resend for automated email communications, including notifications and updates.