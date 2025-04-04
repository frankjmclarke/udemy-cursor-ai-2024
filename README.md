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

## Project Architecture

### Technology Stack
- Next.js 14 with App Router
- React 18
- TypeScript
- Tailwind CSS for styling
- ESLint for code quality

### Project Structure
```
├── src/
│   ├── app/                 # Next.js 14 App Router
│   │   ├── layout.tsx       # Root layout component
│   │   ├── page.tsx         # Home page component
│   │   ├── globals.css      # Global styles
│   │   └── fonts/          # Custom fonts
│   └── lib/
│       └── utils.ts         # Utility functions
├── public/                  # Static assets
├── components/              # Reusable UI components
└── seed-data/              # Data seeding files
```

### Key Features
- Modern Next.js App Router architecture
- Component-based architecture with class-variance-authority for styling variants
- Lucide React for icons
- Tailwind CSS with animations support
- TypeScript for type safety

### Development Commands
- `npm run dev` - Start development server
- `npm run build` - Create production build
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

### Styling Approach
- Tailwind CSS for utility-first styling
- Global styles in `globals.css`
- Component-specific styles using Tailwind classes
- Support for animations through tailwindcss-animate

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
# udemy-cursor-ai-2024
