# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

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
│   └── pages/
│       └── index.astro
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

Principales características de Astro:
Optimización de rendimiento: Astro solo carga el JavaScript necesario, lo que permite crear sitios ultrarrápidos. Si un componente no necesita JavaScript en el cliente, Astro lo evita.

Islas de componentes: Una de sus principales innovaciones es el concepto de "Component Islands" (islas de componentes). Esto significa que en lugar de enviar todo el JavaScript al cliente, solo las partes interactivas de la página (los componentes) reciben JavaScript.

Compatible con múltiples frameworks: Astro es agnóstico a los frameworks, lo que significa que puedes usar componentes de React, Vue, Svelte, Preact, o incluso mezclarlos en el mismo proyecto.

Generador de sitios estáticos: Aunque Astro puede manejar componentes dinámicos, está diseñado principalmente como un generador de sitios estáticos. Esto significa que puede pre-renderizar páginas durante el proceso de construcción para servir HTML estático, lo que mejora mucho la velocidad de carga.

No depende de JavaScript en el cliente: A diferencia de otros frameworks que envían grandes cantidades de JavaScript al navegador, Astro se enfoca en reducir la cantidad de JavaScript en el cliente, haciéndolo ideal para sitios donde el rendimiento es crítico.