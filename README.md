This is landing page created using [https://tailblocks.cc/](Tailblocks.cc) from [https://www.youtube.com/@hqasmei](Honsa Qasmei Youtube Channel).
My first time knowing about Tailblocks.cc. Super useful, super simple, super clean and good.

# Initialization

## Pre Setup

1. Create `components` and `styles` folder. Move `globals.css` to `styles` folder.
2. Remove everything inside `page`.
3. Clean the `globals.css`.

## Header

1. Create `header.tsx` and copy from `Tailblocks`. Make sure to rename `class` to `className`.
2. Inside `layout`, import the `Header` and insert into the `body`.

## Footer

1. Create `footer.tsx` and copy from `Tailblocks`.
2. Import to `layout` and insert into the `body` after `children`.

## Hero

1. Create `hero-section` and copy from `Tailblocks`.
2. Import to `page` and insert into the `main`.

## Content

1. Create `content` and copy from `Tailblocks`.
2. Import to `page` and insert after `HeroSection`.

## Feature

1. Create `feature` and copy from `Tailblocks`.
2. Import to `page` and insert after `Content`.

## Contact

1. Create `contact` and copy from `Tailblocks`.
2. Import to `page` and insert after `Feature`. Create self-closing tag and remove `for` tag.
3. Import to `page` and insert after `Feature`.

# Creating a Dynamic Navbar Shadow Effect

Create a custom hook that recognizes when we scroll down.

1. Create folder called `hooks` and create new file `useScrollPosition`.
2. Use `use client` and import `useState` and `useEffect`.
3. Create a logic for `useState` and `useEffect`.
4. Import `useScrollPosition` to `header`.

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
