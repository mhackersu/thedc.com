# The Digital Catechism

Open-Source Simplified Catechism

## Clone

Clone the repository:

```bash
git clone https://github.com/mhackersu/thedc.com
```

## Setup

Install dependencies:

```bash
yarn install
```

## Development

```bash
yarn dev
```

## Edge Side Rendering

Can be deployed to Vercel Functions, Netlify Functions, AWS, and most Node-compatible environments.

Look at all the available presets [here](https://v3.nuxtjs.org/guide/deploy/presets).

  ```bash [npm]
  npm install
  ```

  ```bash [yarn]
  yarn install
  ```

  ```bash [pnpm]
  pnpm install --shamefully-hoist
  ```

## Static Generation

Use the `generate` command to build your application.

The HTML files will be generated in the .output/public directory and ready to be deployed to any static compatible hosting.

```bash
yarn generate
```

## Preview build

You might want to preview the result of your build locally, to do so, run the following command:

```bash
yarn preview
```

---

For a detailed explanation of how things work, check out the Docus [docs](https://docus.dev).
