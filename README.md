# issues-to-website

## to do

- edit issue should work. right now it fails, because integromat doesn't get SHA
- github page from `.md`s
    - ich will eine seite (similar to a 'blog overview page')
    - die hat viele box components
    - die jeweils von einem .md gefeeded werden
- can integromat trigger from webhook instead of `every 15 minutes`?


## alternative approaches

### local

https://github.com/maxlath/backup-github-repo
https://github.com/mattduck/gh2md
https://github.com/jlord/offline-issues

### github actions

https://github.com/marketplace/actions/transfer-github-project-issues-into-google-sheets
https://github.com/marketplace/actions/export-issues

---

uses `react-markdown`, `gray-matter`, `raw-loader`, `react-syntax-highlighter`

---

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
