# Vite + React + Tailwind CSS starter

Based on [wobsoriano's](https://github.com/wobsoriano) [vite-react-tailwind-starter](https://github.com/wobsoriano/vite-react-tailwind-starter), that recently moved codebase to TypeScript

## Using

### Installation

```sh
yarn
```

### Development

```sh
yarn dev
```

### Build

```sh
yarn build
```

### Serve (preview)

```sh
yarn serve
```

## Tailwind UI

If you have access to [Tailwind UI](https://tailwindui.com), you can follow the following steps to add it:

1. Install `@tailwindcss/ui`:

```sh
yarn add @tailwindcss/ui
```

2. Add the plugin in `tailwind.config.js` without changing anything else:

```js
// tailwind.config.js
module.exports = {
  // ...
  // rest of the config
  plugins: [require('@tailwindcss/ui')],
}
```

## TypeScript

Use [this example](https://github.com/wobsoriano/vite-react-tailwind-starter) by wobsoriano

## License

Licensed under [MIT](LICENSE)