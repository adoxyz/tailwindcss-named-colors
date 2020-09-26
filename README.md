# tailwindcss-named-colors

This plugin adds all
[140 named CSS colors](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
to your TailwindCSS project. Currently the plugin enables you to set the
background or text color using any of the named colors.

## Install

```
npm install @adoxyz/tailwindcss-named-colors
```

In your `tailwind.config.js` file, load the plugin:

```
module.exports = {
  purge: false,
  theme: {},
  variants: {},
  plugins: [
    require('@adoxyz/tailwindcss-named-colors'),
  ],
}
```

## Use:

Backgrounds:

```
<div class="bg-salmon">

</div>
```

Text:

```
<h1 class="text-tomato">Hello</h1>
```
