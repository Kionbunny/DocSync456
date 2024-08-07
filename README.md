# LiveDocs

LiveDocs is a SaaS-based collaborative text editor designed to provide real-time, feature-rich document creation and editing. Leveraging cutting-edge technologies, LiveDocs allows multiple users to interact live, offering both "edit" and "view" functionalities with seamless real-time updates.

## Features

- **Real-Time Collaboration**: Multiple users can edit and view documents simultaneously with live updates.
- **User Authentication**: Supports GitHub and Google-based sign-in via Clerk.
- **Notifications**: Get notified about shares, changes, comments, and mentions.
- **Advanced Commenting**: Alongside overall commenting and tagging feature, comment on specific words or sections and tag users using `@username` or `@emailAddress` to talk on it.
- **Rich User Interface**: Built with Radix UI and styled using Tailwind CSS and Shadcn for a modern, responsive design.

## Tech Stack

- **Next.js**: React framework for server-side rendering and static site generation.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **Clerk**: Authentication and user management.
- **Liveblocks**: Real-time collaboration infrastructure.
- **Radix UI**: Primitives for building accessible, high-quality UI components.
- **Shadcn**: A utility library for styling and component composition.
- **React**: JavaScript library for building user interfaces.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
