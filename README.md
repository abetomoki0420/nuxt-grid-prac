# Nuxt 3 Grid Layout Demo

[Demo](https://gallant-edison-7a136e.netlify.app/)

Grid Layout practice witch [Nuxt3](https://v3.nuxtjs.org/) and [Tailwind CLI](https://tailwindcss.com/docs/installation#using-tailwind-cli)

## Integrating Tailwind into Nuxt3 with Tailwind CLI

Generating `tailwind.css` file to use Tailwind CLI.

```
npx tailwindcss -o tailwind.css
```

To use the `tailwind.css`, config [css](https://v3.nuxtjs.org/docs/directory-structure/nuxt.config#css) property in `nuxt.config.ts`.

```
import { defineNuxtConfig } from "nuxt3"

export default defineNuxtConfig({
  css: ["@/tailwind.css"],
})

```
