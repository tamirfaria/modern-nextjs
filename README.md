# Modern NextJS

> 🖌️ Creating and implementing a modern NextJS 13 website with Framer Motion and Tailwind CSS

## Stack

* [🖥️ NextJS 13](https://nextjs.org/)
* [🖌️ Tailwind CSS](https://tailwindcss.com/)
* [📺 Frame Motion](https://www.framer.com/motion/)
* [🎨 Figma](https://www.figma.com/file/EyzNoOFak1Nb1bBx9ZKI7E/Modern-UI%2FUX-Framer-Motion?type=design&node-id=1%3A56&mode=dev)

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

## Folders Schema

📁 app

```∟ core```

📁 components

```∟ functions that may or may not receive parameters and are embedded in a page;```

📁 constants

```∟ file containing arrays of objects with content that will be consumed by the components;```

📁 pages

```∟ application screens that will be connected to routes;```

📁 public

```∟ images, icons, and other graphic items;```

📁 sections

```functions that may or may not receive parameters and serve as clusters of "components". They are also incorporated into the pages;```

📁 styles

```∟ location where global styles, style variables will be placed;```

📁 utils

```∟ functions that will handle small manipulations, such as conversions, renderings, and conditional styles;```

## Soon

>Soon the project will be deployed at [▲ Vercel](https://vercel.com/), and will have CI/CD configuration with [GitHub Actions](https://docs.github.com/pt/actions).
