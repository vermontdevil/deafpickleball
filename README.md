<h1>Deaf Pickleball USA</h1>


## Contents

- [Project overview](#project-overview)

- [Credits](#credits)

---

## Project Overview

- Deaf Pickleball website

- The project uses [Eleventy](https://11ty.dev) as a static site generator
- Default templating is [Nunjucks](https://mozilla.github.io/nunjucks/) (can be changed)
- PostCSS set up to handle:
	- TailwindCSS
	- CSS Imports
	- Autoprefixer
- PurgeCSS to remove unused CSS (set up for TailwindCSS by default) in production
- HTML minified in production
- CSS inlined and minified in production
- [esbuild](https://esbuild.github.io/) used to bundle and minify scripts
- Document `<head>` crafted using [htmlhead.dev](https://htmlhead.dev)


---

#### Credits

- [Eleventy](https://11ty.dev)
- [TailwindCSS](https://tailwindcss.com/)
- [PostCSS](https://github.com/postcss)
	- Autoprefixer
	- PostCSS Import
- [esbuild](https://esbuild.github.io/)
- [Luxon](https://moment.github.io/luxon/)
- [NPM Run All](https://www.npmjs.com/package/npm-run-all)
- [HTML Minifier](https://www.npmjs.com/package/html-minifier)