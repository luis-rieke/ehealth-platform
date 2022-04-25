<p align="center">
<img src="./public/elefant.png" style="width: 50%;">
</p>

<h1 align="center">eHealth Data platform</h1>

This is my repo for the eHealth Data platform I'm building for my bachelor thesis.
My scientific goal is to find ways to manage sensible data within a serverless cloud infrastructure.

## Links and external ressources

[Astro documentation](https://github.com/withastro/astro)

## Installing & Running

### Prerequisites:

- Node v16 or later (check version using `node -v`)

### Commands:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## Project Structure

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

There's nothing special about `src/components/`, but that's where Astro/React/Vue/Svelte/Preact components are meant to be.

Any static assets, like images, can be placed in the `public/` directory.
