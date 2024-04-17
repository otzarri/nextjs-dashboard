## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Tutorial

The initial content of this repository was created with this command:

```
npx create-next-app@latest nextjs-dashboard --use-npm --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example"
```

## Directory structure

- **/app**: Contains all the routes, components, and logic for your application, this is where you'll be mostly working from.
- **/app/lib**: Contains functions used in your application, such as reusable utility functions and data fetching functions.
- **/app/ui**: Contains all the UI components for your application, such as cards, tables, and forms. To save time, we've pre-styled these components for you.
- **/public**: Contains all the static assets for your application, such as images.
- **/scripts**: Contains a seeding script that you'll use to populate your database in a later chapter.
- **Config Files**: You'll also notice config files such as next.config.js at the root of your application. Most of these files are created and pre-configured when you start a new project using create-next-app. You will not need to modify them in this course.
- **Placeholder data**: The placeholder data is provided in[app/lib/placeholder-data.js](./app/lib/placeholder-data.js). Each JavaScript object in the file represents a table in the database.
- **TypeScript**: The types that will be returned from the database are defined in[/app/lib/definitions.ts](/app/lib/definitions.ts).

## Running the development server

Install dependencies:

```
npm i
```

Start the development server:

```
npm run dev
```

