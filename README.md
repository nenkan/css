# Nenkan CSS

## Installation

```sh
npm install @nenkan/css
```

If you want to include the Sass version:

```js
import '@nenkan/css'
```

If you want to use the compiled CSS version:

```js
import '@nenkan/css/dist/index.css'
```

If you want to use a CDN version:

```html
<link rel="stylesheet" href="https://unpkg.com/@nenkan/css@0.10.0/dist/index.css">
```

## Deployment

Bump the `version` property in package.json. Make sure to update any other relevant files where a new version should be specified. Then, commit that and tag that commit with the version in the format: `vX.Y.Z`, where X is the major version, Y the minor version, and Z the patch version. For example: `v0.8.0`.

```sh
git tag -a v0.8.0

git push --tags
```

Compile the CSS for distribution:

```sh
npm run build
```

Finally, publish to NPM:

```sh
npm publish
```
