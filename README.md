# Chris Breuer's Blog [![Netlify Status](https://api.netlify.com/api/v1/badges/8c53b581-2507-40fa-badd-1de349441175/deploy-status)](https://app.netlify.com/sites/chrisbreuer/deploys)

> A simple, hackable & minimalistic starter for Gridsome that uses Netlify CMS for content.

## Features

- Beautiful and simple design.
- Markdown for content.
- Tags support.
- Dark / Light toggle.
- CSS variables, SCSS & BEM for styling.
- 100, 100, 100, 100 score on Google Lighthouse.
- Uses same front-matter fields as Dev.to.

## Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/suits-at/netlifycms-gridsome)

### Enable Identity

Enable the netlify identity service at https://app.netlify.com/sites/YOUR-SITE/settings/identity. For exact instructions see https://www.netlify.com/docs/identity/. You might want to enable Git Gateway as well https://www.netlify.com/docs/git-gateway/.

### Edit content

Access `chrisbreuer.co/admin`, e.g. `chrisbreuer.netlify.com/admin` or locally this might be  `localhost:3000/admin`.

## Install locally

### 1. Install Gridsome CLI tool if you don't have

`npm install --global @gridsome/cli`

### 2. Install this starter

1. `gridsome create my-gridsome-site https://github.com/suits-at/netlifycms-gridsome`
2. `cd my-gridsome-site` to open folder
3. `gridsome develop` to start local dev server at `http://localhost:8080`
4. Happy coding 🎉🙌
