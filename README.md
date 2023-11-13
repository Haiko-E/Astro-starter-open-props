# Astro Starter Kit: Basics

Clone this repo and install with following command

```sh
npm install
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   |   └── index.astro
|   └── styles/
│       └── styles.scss
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## 👀 Open props added to starter

go to [Open Props Website](https://open-props.style/) and checkout all utils you can add to your project.

In the scss folder you can find [Utopia](https://utopia.fyi/) responsive variables you can use to create responsive spaces and typography.

## 👀 Settings to change autocomplete on variables

Add `CSS Var Complete` to your vs-code to get autocomplete on you variables

Press `crtl p` and type `settings`. open vs code settings.json

add this to your json file

```
"cssvar.files": [
    "./node_modules/open-props/open-props.min.css",
    "./node_modules/open-props/colors-hsl.min.css",
    // if you have an alternative path to where your styles are located
    // you can add it in this array of files
    "assets/styles/variables.css",
    "./**/*/*.scss"
  ],

  // Do not ignore node_modules css files, which is ignored by default
  "cssvar.ignore": [],

  // add support for autocomplete in JS or JS like files
  "cssvar.extensions": ["scss", "css", "postcss", "jsx", "tsx", "vue", "astro"],
```
