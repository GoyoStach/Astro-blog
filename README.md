# Blog Demo
© 2023 Guillaume Excoffier. All rights reserved.
## 🧾Context

This project have the goal creating a template blog to expose `.md` notes to the web. The idea of developping such a tool came to me when i saw a video of [Takuya Matsuyama](https://github.com/craftzdog) :

[![# How to create a 'What I Use' blog with Astro and Tailwind CSS](https://img.youtube.com/vi/3_JE76PKBWE/maxresdefault.jpg)](https://www.youtube.com/watch?v=3_JE76PKBWE)

## 📚Stack

- 🚀[Astro](https://astro.build/) - Astro is an **all-in-one** **web framework** for building **fast,** **content-focused** websites.
- ⚛[React](https://beta.reactjs.org/) - A JavaScript library for building user interfaces
- ⌨[Tailwind](https://tailwindcss.com/) - Rapidly build modern websites without ever leaving your HTML.

## 📁Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
├── public/
│   └── Images/
│        ├──[Project_1]
│        │       ├──Image1.png
│        │       └──Image2.png
│        ├──[Project_2]
│        └──[Project_n]
├── src/
│   ├── components/
│   ├── layouts/
│   └── content/
│    	└── Project_1.md
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Each `.md` file have a dedicated folder in the `public/Images` folder where you can store your static assets so that those dont get mixed up.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |

## 🚀Deploying

I would advide to push your code to your own git repository. 
I used [Vercel](https://vercel.com/dashboard) to deploy. It is a free & easy to setup option as long as you are not using your website for commercial use. 

