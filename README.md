# bonsai pack 4

with Pug / SCSS / TS / React / Linter / Formatter / Hooks

## Usage

### Install

```.bash
$ yarn

#or

$ yarn install
```

### Develop

```.bash
$ yarn dev
```

### Build

```.bash
$ yarn build
```

## Structure

### assets

-   scripts: TypeScript files
-   styles: Scss files
-   pugs: layouts, modules, mixins
-   react: react

### public

meta files(favicon.ext, .htaccess)

### Other directories

To be used for a pages in the website

## node modules

### style

-   modern-normalize
-   @unocss/reset

## Build modules

-   Vite
    -   vite
    -   @vitejs/plugin-react
    -   @macropygia/vite-plugin-connect-middleware
    -   @macropygia/vite-plugin-glob-input
    -   @macropygia/vite-plugin-imagemin-cache
    -   @macropygia/vite-plugin-pug-static
-   Pug
    -   pug
-   SCSS
    -   sass
    -   postcss
    -   autoprefixer
    -   css-declaration-sorter
    -   postcss-csso
    -   postcss-sort-media-queries
-   TypeScript
    -   typescript
    -   ts-node
    -   @tsconfig/node16-strictest-esm
-   Library
    -   react
    -   react-dom
-   Linter/Formatter
    -   ESLint
        -   eslint
        -   @typescript-eslint/eslint-plugin
        -   @typescript-eslint/parser
        -   eslint-config-prettier
        -   eslint-import-resolver-typescript
        -   eslint-plugin-import
        -   eslint-plugin-prettier
        -   eslint-plugin-react
        -   eslint-plugin-react-hooks
        -   eslint-plugin-tsdoc
    -   Prettier
        -   prettier
        -   @prettier/plugin-pug
    -   Stylelint
        -   stylelint
        -   stylelint-config-prettier
        -   stylelint-config-recommended-scss
        -   stylelint-prettier
    -   EditorConfig
-   Git Hooks
    -   simple-git-hooks
    -   lint-staged
