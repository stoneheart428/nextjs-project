# Next.js Projects

This repo is made of 5 projects:

1. [**NextEvents**](#nextevents): A social networking site using Next.js, MongoDB and Firebase.
2. [**Blog**](#blog): A complete app example with a blog using Next.js, MongoDB, Markdown and React Syntax Highlighter.
3. [**Dashboard**](#dashboard): A very simple dashboard to understand authentication with NextAuth.js.
4. [**React Meetups**](#reactmeetups): Another social networking site to summarize Next.js core concepts.
5. [**DJ Events**](#djevents): A music event website using Strapi CMS as backend.

## <a name="nextevents"></a>1) NextEvents

A social networking site using Next.js, MongoDB and Firebase.

[See Demo deployed on Vercel](https://nextevents.vercel.app/)

[See 01-nextevents folder](https://github.com/solygambas/next-course/tree/main/01-nextevents)

<p align="center">
    <a href="https://github.com/solygambas/next-course/tree/main/01-nextevents">
        <img src="01-nextevents/screenshot.png">
    </a>
</p>

### Features

- working with file-based routing and handling dynamic routes.
- creating a general layout, adding React components and styling them with CSS modules.
- displaying events and filtering them by date.
- adding Static Site Generation (SSG) on the home page.
- fetching events from Firebase and enabling page pre-rendering for dynamic pages.
- using Server-Side Rendering (SSR) and client-side data fetching with SWR.
- adding metadata with Head.
- customizing the \_app.js and \_document.js files.
- optimizing images with Image.
- handling comments and signups for the newsletter with API routes.
- setting up a MongoDB database and getting comments for a specific event.
- handling errors and displaying user-friendly notifications.
- deploying on Vercel.

## <a name="blog"></a>2) Blog

A complete app example with a blog using Next.js, MongoDB, Markdown and React Syntax Highlighter.

[See Demo deployed on Vercel](https://next-dagny.vercel.app/)

[See 02-blog folder](https://github.com/solygambas/next-course/tree/main/02-blog)

<p align="center">
    <a href="https://github.com/solygambas/next-course/tree/main/02-blog">
        <img src="02-blog/screenshot.png">
    </a>
</p>

### Features

- building the home page, creating a general layout and a reusable grid to display the latest posts.
- reading markdown files and rendering posts as JSX with gray-matter and react-markdown.
- displaying dynamic post pages and generating paths.
- optimizing images from markdown with Image.
- rendering code snippets from markdown and optimizing React Syntax Highlighter bundle size.
- handling messages sent by users via an API route.
- storing messages in a database with MongoDB.
- adding metadata in Head and customizing \_document.js file.
- using React portals to show user-friendly notifications.
- deploying on Vercel.

## <a name="dashboard"></a>3) Dashboard

A very simple dashboard to understand authentication with NextAuth.js.

[See 03-dashboard folder](https://github.com/solygambas/next-course/tree/main/03-dashboard)

<p align="center">
    <a href="https://github.com/solygambas/next-course/tree/main/03-dashboard">
        <img src="03-dashboard/screenshot.png">
    </a>
</p>

### Features

- adding a user signup API route and sending signup requests from the frontend.
- hashing passwords with Bcryptjs.
- working with a custom auth provider in NextAuth.js to log in users.
- managing active sessions and handling logouts.
- protecting routes with client-side and server-side page guards.
- protecting API routes.
- enabling users to change their passwords.

## <a name="reactmeetups"></a>4) React Meetups

Another social networking site to summarize Next.js core concepts.

[See 04-reactmeetups folder](https://github.com/solygambas/next-course/tree/main/04-reactmeetups)

<p align="center">
    <a href="https://github.com/solygambas/next-course/tree/main/04-reactmeetups">
        <img src="04-reactmeetups/screenshot.png">
    </a>
</p>

### Features

- converting a React project into a Next.js app.
- handling server-side rendering of pages with getStaticProps and getStaticPaths.
- connecting and querying a MongoDB Database via an API route.
- getting data from the database for page pre-rendering.
- working with fallback pages and revalidation to display new meetups without having to rebuild.

## <a name="djevents"></a>5) DJ Events

A music event website using Strapi CMS as backend.

[See Demo deployed on Vercel](https://next-djevents-strapi.vercel.app/)

[See Strapi API deployed on Heroku](https://djevents-strapi.herokuapp.com/events)

[See 05-djevents folder](https://github.com/solygambas/next-course/tree/main/05-djevents)

<p align="center">
    <a href="https://github.com/solygambas/next-course/tree/main/05-djevents">
        <img src="05-djevents/screenshot.png">
    </a>
</p>

### Features

-

This repository is based on 2 courses:

- [Next.js & React - The Complete Guide](https://www.udemy.com/course/nextjs-react-the-complete-guide/) by Maximilian Schwarzmüller (2021).
- [Next.js Dev to Deployment](https://www.udemy.com/course/nextjs-dev-to-deployment/) by Brad Traversy (2021).
