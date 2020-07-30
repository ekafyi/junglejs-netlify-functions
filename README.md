# JungleJS + Netlify Functions starter site

<p align="center"><img src="https://image.flaticon.com/icons/svg/2950/2950532.svg" width="80" height="80" alt="" />&nbsp;&nbsp;<img src="https://seeklogo.com/images/N/netlify-logo-758722CDF4-seeklogo.com.png" width="80" height="80" alt="" style="margin-left:1rem"/></p>

A starter site with:

- [JungleJS](https://www.junglejs.org) — Svelte and GraphQL-based static site generator
- [Netlify Functions](https://www.netlify.com/products/functions/) — Serverless functions
- [Storybook](https://storybook.js.org) — UI development environment
- [TailwindCSS](https://tailwindcss.com) — utility-first CSS framework

Based on my previous starter site, https://github.com/ekafyi/junglejs-storybook-tailwind

Introductory posts:
- [Go serverless with this JungleJS + Netlify functions starter site](https://dev.to/ekafyi/go-serverless-with-this-junglejs-netlify-functions-starter-site-3bg0)
- [Getting Started with Netlify Functions](https://dev.to/ekafyi/getting-started-with-netlify-functions-part-1-zero-config-setup-and-writing-our-first-functions-1i5b)

## One-click deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/git?s=https%3A%2F%2Fgithub.com%2Fekafyi%2Fjunglejs-netlify-functions%2Ftree%2Fmaster) [![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/ekafyi/junglejs-netlify-functions)

Or [create a new repo](https://github.com/ekafyi/junglejs-netlify-functions/generate) with Github template.

## Installation

```bash
git clone https://github.com/ekafyi/junglejs-netlify-functions.git
cd junglejs-netlify-functions

# Install dependencies
npm install

# Start Netlify Dev server
netlify dev

# (Optional) Start Storybook server in a separate tab
npm run storybook
```

Netlify Dev serves your site on `localhost:3333`. Your functions run on `localhost:3333/.netlify/functions/{YOUR_FUNCTION_NAME}`. 

This starter comes with a sample function `hello.js`, which you can access on:
- localhost:3333/.netlify/functions/hello
- localhost:3333/.netlify/functions/hello?name=Eka (example with query parameter)

If you start it, Storybook runs on `localhost:6006`.

## Credits

Boilerplate code from [Jungle template](https://github.com/junglejs/template). Repo icon/logo by [Freepik](http://www.freepik.com) from [Flaticon](https://www.flaticon.com).

---

(c) 2020 Eka MIT License
