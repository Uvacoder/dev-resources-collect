---
title: Svelte
logo: ''
description: ''
byline: Cybernetically enhanced web apps
wikipedia_excerpt: ''
key_links:
  homepage: https://svelte.dev/
  docs: https://svelte.dev/docs
  wiki: ''
  pkg_url: ''
  pkg_registry: ''
  repo_nwo: sveltejs/svelte
  wikipedia: ''
  learn_x: ''
  devhints: ''
  tutorials_point: ''
  rosetta_code: ''
links:
- title: Svelte Vite quickstart template
  url: https://github.com/MichaelCurrin/svelte-vite-quickstart
documentation:
- title: Examples
  url: https://svelte.dev/examples
  description: ''
tutorials:
- title: Official tutorial
  url: https://svelte.dev/tutorial/
- title: 'Svelte in 100 Seconds '
  url: https://youtu.be/rv3Yq-B8qp4
  description: ''
- url: https://svelte.dev/tutorial/basics
  description: Starting point for the tutorial on the Svelte site
  title: Basics
- title: The easiest way to get started with Svelte
  url: https://svelte.dev/blog/the-easiest-way-to-get-started
  description: On the Svelte blog
  
blog_posts: []

playgrounds:
- title: REPL
  url: https://svelte.dev/repl/hello-world?
  description: Playground on the Svelte website
link_sections: []

---
> Svelte is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the _browser_, Svelte shifts that work into a _compile step_ that happens when you build your app.

Definition of the world "svelte": 
  
> _[adjective] slender, lithe. having clean lines : sleek._

   
### Installation

```sh
$ npm install svelte
```

### Usage

Start dev server:

```sh
$ npm run dev
```

Build:

```sh
$ npm run build
```

### Quickstart

Using [sveltejs/template](https://github.com/sveltejs/template) repo and [degit](https://www.npmjs.com/package/degit) tool.

```sh
npx degit sveltejs/template my-svelte-project
cd my-svelte-project

# To use TypeScript:
node scripts/setupTypeScript.js

npm install
npm run dev
```
