# Gatsby Starter: Minimal Blog

Typography driven, focus on the content & minimal style. Powered by MDX.

[![Netlify Status](https://api.netlify.com/api/v1/badges/5cd44dfb-b734-457b-8275-d049bb89d028/deploy-status)](https://app.netlify.com/sites/markusheilig/deploys)

## About Me

I hope you like my starters and create something awesome! To see some of my work you can visit my [website](https://www.lekoarts.de) or support me on [Patreon](https://www.patreon.com/lekoarts) to get some neat rewards (4K images, project files, tutorial insights). Every pledge on Patreon helps me creating more free starters!

Also check out the other _gatsby-starters_:

- [gatsby-starter-portfolio-emma](https://github.com/LekoArts/gatsby-starter-portfolio-emma)
- [gatsby-starter-portfolio-emilia](https://github.com/LekoArts/gatsby-starter-portfolio-emilia)
- [gatsby-starter-portfolio-bella](https://github.com/LekoArts/gatsby-starter-portfolio-bella)
- [gatsby-starter-portfolio-cara](https://github.com/LekoArts/gatsby-starter-portfolio-cara)
- [gatsby-starter-portfolio-jodie](https://github.com/LekoArts/gatsby-starter-portfolio-jodie)
- [gatsby-starter-prismic](https://github.com/LekoArts/gatsby-starter-prismic)
- [gatsby-starter-prismic-i18n](https://github.com/LekoArts/gatsby-starter-prismic-i18n)

Check out the [Gatsby Starter Portfolio Overview](https://gatsby-starter-portfolio.netlify.com/)!

## Features

- Articles in MDX ([gatsby-mdx](https://github.com/ChristopherBiscardi/gatsby-mdx))
- Code highlighting (with [prism-react-renderer](https://github.com/FormidableLabs/prism-react-renderer)) and live preview (with [react-live](https://github.com/FormidableLabs/react-live))
- Styled Components 💅
- Netlify Contact Form
- Categories
- Offline Support
- WebApp Manifest Support
- SEO
  - Sitemap
  - Schema.org JSONLD
  - OpenGraph Tags
  - Twitter Tags

## Getting Started

Check your development environment! You'll need [Node.js](https://nodejs.org/en/), the [Gatsby CLI](https://www.gatsbyjs.org/docs/) and [node-gyp](https://github.com/nodejs/node-gyp#installation) installed. The official Gatsby website also lists two articles regarding this topic:

- [Gatsby on Windows](https://www.gatsbyjs.org/docs/gatsby-on-windows/)
- [Check your development environment](https://www.gatsbyjs.org/tutorial/part-zero/)

To copy and install this starter run this command (with "project-name" being the name of your folder you wish to install it in):

```
gatsby new project-name https://github.com/LekoArts/gatsby-starter-minimal-blog
cd project-name
npm run develop
```

### Adding new features/plugins

You can add other features by having a look at the official [plugins page](https://www.gatsbyjs.org/docs/plugins/)

### Building your site

```
npm run build
```

Copy the content of the `public` folder to your webhost or use a website like Netlify which automates that for you.

**Attention:** You also need to edit `static/robots.txt` to include your domain!
