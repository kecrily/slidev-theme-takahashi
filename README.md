# slidev-theme-takahashi

[![NPM version](https://img.shields.io/npm/v/slidev-theme-takahashi?color=3AB9D4&label=)](https://www.npmjs.com/package/slidev-theme-takahashi)

A **simple** theme for [Slidev](https://github.com/slidevjs/slidev).

<!--
  Learn more about how to write a theme:
  https://sli.dev/themes/write-a-theme.html
--->

<!--
  run `npm run dev` to check out the slides for more details of how to start writing a theme
-->

<!--
  Put some screenshots here to demonstrate your theme

  Live demo: [...]
-->

![How to start](./screenshots/07.png)

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

<pre><code>---
theme: <b>takahashi</b>
---</code></pre>

Learn more about [how to use a theme](https://sli.dev/themes/use).

## Layouts

This theme provides only two styles, `default` and `reverse`.

`default`

![](./screenshots/01.png)
![](./screenshots/02.png)
![](./screenshots/03.png)
![](./screenshots/06.png)

`reverse`

![](./screenshots/05.png)

## Contributing

- `pnpm install`
- `pnpm dev` to start theme preview of `example.md`
- Edit the `example.md` and style to see the changes
- `pnpm export` to generate the preview PDF
- `pnpm screenshot` to generate the preview PNG
