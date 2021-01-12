# cra-template-typescript-sass

This is TypeScript + Sass based on the official TypeScript template for [Create React App](https://github.com/facebook/create-react-app).

## Additional changes

You may want to add `"baseUrl": "src"` to the `compilerOptions` in `tsconfig.json`
so as to be able to use absolute paths in `import` statements.

## How to use the template

This template is not published to npm.

Therefore, you need to clone the repo, and run the following command to create a new app.

```
npx create-react-app my-app --template file:/path/to/your/template/cra-template-typescript-sass

# or

yarn create react-app my-app --template file:/path/to/your/template/cra-template-typescript-sass
```

## More information

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.
