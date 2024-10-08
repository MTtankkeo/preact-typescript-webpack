<div align="center">
  <img width="200px" src="https://github.com/user-attachments/assets/13a366f0-8dce-4301-a275-50aa8c7f1686">
  <h1>Preact with Typescript</h1>
  <span>This is template that is simple start-kit about Preact with Typescript.</span><br>
  <a href="https://github.com/MTtankkeo/preact-typescript-node">Go to related Node.ts template</a>
</div>

<br>

> __Refer to localization docs__<br>
> [Korean](README-kr.md)

# Configuration
1. Webpack `Bundler`
2. Webpack Dev Server `for hot reload`
3. Preact
4. [Wouter](https://www.npmjs.com/package/wouter)
5. Typescript
6. Javascript minimizer `Used by terser`
7. CSS minimizer `Used by 'css-minimizer-webpack-plugin'`
8. CSS loader
9. SVG loader `Used by preact-svg-loader`

# Build by NPM
To a smooth and fast development environment, ensure that any changes on the client side are automatically detected and built without the need to repeatedly run `npm run build`.

> Starting from the root directory, enter the following command in the terminal in `./`.

```cli
npm run serve
```

| Type | Description |
| ---- | ----------- |
| build | Builds in production mode after undergoing optimization and compression processes for a better user experience.
| build:dev | Needs to be built as quickly as possible, so the optimization and compression steps are skipped and builds in development mode.
| watch | Builds in production mode, and automatically rebuilds when changes occur.
| watch:dev | Needs to be built as quickly as possible, so the optimization and compression steps are skipped. Additionally, automatically rebuilds when changes occur.
| serve | Needs to be built as quickly as possible, so the optimization and compression steps are skipped, and the resources are cached. Additionally, only the changes are rebuilt, and the website automatically refreshes.
