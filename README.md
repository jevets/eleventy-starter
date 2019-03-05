A simple [Eleventy](https://www.11ty.io/) starter project with separate src/dist directories and a few npm scripts.

This is the project layout I typically set up when starting a new Eleventy project.

### Install

1. Clone the repo and install npm dependencies
1. `yarn dev` for local development server
1. `yarn build` to compile

```
git clone https://github.com/jevets/eleventy-starter.git new-project
cd new-project
yarn
```

### Development

`yarn dev`

Templates are in the `src` folder.

### Build

`yarn build`

Output gets compiled into the `dist` folder.

### Deployment

Upload the `dist` folder's contents to your static host's web root.

Or just use Netlify and set it to run `yarn build` and set the root folder to `dist`.

