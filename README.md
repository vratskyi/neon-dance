# Neon Dance - Free Portfolio Website
![Neon Dance Preview](https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/ac9593159959367.63aa216bf3dff.png)

### Hi everyone! I am happy to show you my first open source project on github.

It is created in the style of Neon Cyberpunk, (*was inspired by cyberpunk 2077*), in general I hope someone will like this project, and on its basis you can create something of your own, of course it is not deprived of technical flaws, such as decomposition and unfinished methods in VueJs, these problems over time I will fix.



# Technologies

 1. **[Nuxt 3](https://nuxt.com/)** - **The Intuitive Web Framework**, Build your next Vue.js application with confidence using Nuxt. An
    open source framework under MIT license that makes web development
    simple and powerful.
    
 2. [**Vue 3**](https://vuejs.org/) - **The  Progressive  JavaScript Framework**, An approachable, performant and versatile framework for building web user interfaces.
 3. **[TailwindCSS](https://tailwindcss.com/)** -  **Rapidly build modern websites without ever leaving your HTML**, A utility-first CSS framework packed with classes like  `flex`,  `pt-4`,  `text-center`  and  `rotate-90`  that can be composed to build any design, directly in your markup.



# Structure

```
📦NUXT-APP
 ┣ 📂.nuxt
 ┣ 📂.output
 ┣ 📂components
 ┃ ┗ 📜PortfolioCards.vue
 ┃ ┗ 📜TheFooter.vue
 ┃ ┗ 📜TheHeader.vue
 ┣ 📂layouts
 ┃ ┗ 📜default.vue
 ┣ 📂pages
 ┃ ┗ 📜index.vue
 ┃ ┗ 📜about.vue
 ┃ ┗ 📜portfolio.vue
 ┃ ┗ 📜services.vue
 ┃ ┗ 📜contact.vue
 ┣ 📂public
 ┣ 📜nuxt.config.ts
 ┣ 📜tailwind.config.js
 ┗ 📜package.json
```

# Nuxt 3 Minimal Starter

Look at the [nuxt 3 documentation](https://v3.nuxtjs.org) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
