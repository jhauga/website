# Website

---

**THIS REPOSITORY HAS BEEN ARCHIVED.** Website is now [part of Flet monorepo](https://github.com/flet-dev/flet/tree/main/website). Read [this announcement](https://flet.dev/blog/flet-v-0-84-release-announcement) for more info.

---

This website is built using [Docusaurus 2](https://v2.docusaurus.io/), a modern static website generator.

View the live site at [https://flet.dev](https://flet.dev).

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

```
$ GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
