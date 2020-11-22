This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.




==========================================

Follow the medium link for installation:
https://medium.com/better-programming/how-to-set-up-next-js-with-tailwind-css-b93ccd2d4164

Problems faced:

As of v2.0, Tailwind CSS depends on PostCSS 8. Because PostCSS 8 is only a few months old, many other tools in the ecosystem haven't updated yet, which means you might see an error like this in your terminal after installing Tailwind and trying to compile your CSS:

## Error: PostCSS plugin tailwindcss requires PostCSS 8.
To help bridge the gap until everyone has updated, we also publish a PostCSS 7 compatibility build under the compat channel on npm.

If you run into the error mentioned above, uninstall Tailwind and re-install using the compatibility build instead:

npm uninstall tailwindcss postcss autoprefixer
npm install tailwindcss@npm:@tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9
