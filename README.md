# Data on Kubernetes Explorer's World

<img src="https://dok.community/img/dokc-logo-white.svg" height="270px"/>

Welcome to the Explorer's world, Here we are trying to rebuild the previously built [Explorer's World](https://explorersworlddok.gtsb.io/). Here we will be implementing the front-end where we will implement the following features

- _Building an application with full scale hydration_
- Making an application with appropriate authentication pages
- Add server-side rendered pages appropriately.



## Project Description

We are working on replicating the existing [Explorer's World](https://explorersworlddok.gtsb.io/). Previously, the repository was using [next.js](nextjs.org/). We are migrating to Astro to allow more flexibility.

### Reasons why we are using Astro
- We become framework agnostic
- It is faster than any other framework
- YOU CAN CODE HTML AS A COMPONENT/PAGE and it still works
- Incredibly easy to work with.

As the project progresses, we will be transferring major components to Astro.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
