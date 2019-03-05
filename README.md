A simple Eleventy starter project with my typical project layout.

### Install

1. Clone the repo and install npm dependencies
1. `yarn dev` for local development
1. `yarn build` to compile

```
git clone https://github.com/jevets/eleventy-starter.git new-project
cd new-project
yarn
# npm install
```

### Development

`yarn dev`

Templates are in the `src` folder.

Output gets compiled into the `dist` folder.

### Deployment

Upload the `dist` folder's contents to your static host's web root.

Or use Netlify and set it to run `yarn build` and root folder of `dist`.

