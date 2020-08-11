# VSCode CSS Snippets

![Cover](https://raw.githubusercontent.com/navin-moorthy/vscode-css-snippets/master/media/cover.jpg)

## Description

Collection of CSS Snippets to make your life easier by auto-completing
[common](#common) css rules, Tailwind utility classes as css rules -
[Tailwind](#tailwind-layout) and [1 line layouts](#1-line-layouts)

It's not debatable, most of us got used to utility classes from
[Tailwind](https://tailwindcss.com/), [BootStrap](https://getbootstrap.com/)
etc,. But when you come back to write plain CSS, wouldn't be great to have those
utility classes converted as snippets instead of typing the CSS rules?

Apart from CSS Utility snippets, collection of snippets from popular CSS
examples found all over the web can be found.

To see the list of all the CSS Snippets, go [here →](#snippets)

Want to have your own favourite CSS Snippets in this extension, see
[Contributing →](#contributing)

![Tailwind Layout snippets Showcase](https://github.com/navin-moorthy/vscode-css-snippets/raw/master/media/vscode-css-snippets.gif)

## Installation

**[Install via the Visual Studio Code Marketplace →](https://marketplace.visualstudio.com/items?itemName=navin-moorthy.vscode-css-snippets)**

You can enable tab completion (recommended) by opening
`Code > Preferences > Settings` (on a Mac) and applying
`"editor.tabCompletion": "onlySnippets"` to your personal settings

## Table of Contents

- [VSCode CSS Snippets](#vscode-css-snippets)
  - [Description](#description)
  - [Installation](#installation)
  - [Table of Contents](#table-of-contents)
  - [Snippets](#snippets)
    - [Common](#common)
      - [CSS Reset](#css-reset)
      - [Pseudo Styles](#pseudo-styles)
      - [Breakpoints](#breakpoints)
    - [Tailwind](#tailwind)
    - [1 line layouts](#1-line-layouts)
  - [Extra Guides](#extra-guides)
    - [Snippets generation from Selected line/lines](#snippets-generation-from-selected-linelines)
  - [Contributing](#contributing)
  - [Attributions](#attributions)

## Snippets

### Common

#### CSS Reset

| Snippet     | Purpose                                                                                                                                                                             |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `css-reset` | An opinionated set of base styles Cloned from [Tailwind Preflight](https://tailwindcss.com/docs/preflight) - [Original File](https://unpkg.com/tailwindcss@1.5.1/dist/tailwind.css) |

#### Pseudo Styles

| Snippet     | Purpose            |
| ----------- | ------------------ |
| `hover`     | :hover             |
| `focus`     | :focus             |
| `active`    | :active            |
| `disabled`  | :disabled          |
| `visited`   | :visited           |
| `first`     | :first-child       |
| `last`      | :last-child        |
| `even`      | :nth-child(2n)     |
| `odd`       | :nth-child(odd)    |
| `nth-child` | :nth-child(`rule`) |

#### [Breakpoints](https://tailwindcss.com/docs/breakpoints)

| Snippet            | Purpose                                                                                                                                             |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| `resp`             | Get all tailwind breakpoints - 640px - 768px - 1024px - 1280px                                                                                      |
| `resp-sm`          | Get tailwind breakpoint - sm - 640px                                                                                                                |
| `resp-md`          | Get tailwind breakpoint - md - 768px                                                                                                                |
| `resp-lg`          | Get tailwind breakpoint - lg - 1024px                                                                                                               |
| `resp-xl`          | Get tailwind breakpoint - xl - 1280px                                                                                                               |
| `resp-selected`    | Get all tailwind breakpoints for selected class/classes - 640px - 768px - 1024px - 1280px [See how →](#snippets-generation-from-selected-linelines) |
| `resp-sm-selected` | Get tailwind breakpoint for selected class/classes - sm - 640px [See how →](#snippets-generation-from-selected-linelines)                           |
| `resp-md-selected` | Get tailwind breakpoint for selected class/classes - md - 768px [See how →](#snippets-generation-from-selected-linelines)                           |
| `resp-lg-selected` | Get tailwind breakpoint for selected class/classes - lg - 1024px [See how →](#snippets-generation-from-selected-linelines)                          |
| `resp-xl-selected` | Get tailwind breakpoint for selected class/classes - xl - 1280px [See how →](#snippets-generation-from-selected-linelines)                          |

### [Tailwind](https://tailwindcss.com/)

- Layout Snippets
- FlexBox Snippets
- Grid Snippets
- Spacing Snippets

### [1 line layouts](https://1linelayouts.glitch.me/)

**[Learn 1linelayouts in detail from Web Dev →](https://web.dev/one-line-layouts/)**

![1 line layout usage](https://github.com/navin-moorthy/vscode-css-snippets/raw/master/media/1linelayouts.gif)

| Snippet                     | Purpose                                                       |
| --------------------------- | ------------------------------------------------------------- |
| `super-centered`            | place-items: center;                                          |
| `deconstructed-pancake`     | flex: 0 1 `baseWidth`};                                       |
| `sidebar-says`              | grid-template-columns: minmax(`min`, `max`) `...`};           |
| `pancake-stack`             | grid-template-rows: auto 1fr auto;                            |
| `classic-holy-grail-layout` | grid-template: auto 1fr auto / auto 1fr auto;                 |
| `12-span-grid`              | grid-template-columns: repeat(12, 1fr);                       |
| `ram`                       | grid-template-columns: repeat(auto-fit, minmax(`base`, 1fr)); |
| `line-up`                   | justify-content: space-between;                               |
| `clamping-my-style`         | clamp(`min`, `actual`, `max`);                                |
| `respect-for-aspect`        | aspect-ratio: `width` / `height`};                            |

## Extra Guides

### Snippets generation from Selected line/lines

![Guide on how to utilize selected lines in snippets](https://raw.githubusercontent.com/navin-moorthy/vscode-css-snippets/master/media/selected-guide.gif)

## Contributing

This is an Open Source Project with MIT License.

You can also contribute to this extension by adding your own list of CSS
Snippets which you think will help others increase their productivity.

See
[Contributing Docs →](https://github.com/navin-moorthy/vscode-css-snippets/blob/master/CONTRIBUTING.md)
for detailed guidance.

## Attributions

**Snippet Ideation:**

- [Tailwind](https://tailwindcss.com/) by
  [Adam Wathan](https://twitter.com/adamwathan) and
  [Steve Schoger](https://twitter.com/steveschoger)
- [1linelayouts](https://1linelayouts.glitch.me/) by
  [Una Kravets 👩🏻‍💻](https://twitter.com/Una)

**Snippet Generation:**

- [Snippet Generator](https://snippet-generator.app/) by
  [Paweł Grzybek](https://twitter.com/pawelgrzybek)

**Docs Inspiration:**

- [Vue VSCode Snippets](https://github.com/sdras/vue-vscode-snippets/blob/master/README.md)
  by [Sarah Drasner](https://twitter.com/sarah_edo)
- [Tailwind Intellisense](https://github.com/tailwindcss/intellisense) by
  [Brad Cornes](https://twitter.com/bradlc)

**Contributing Inspiration:**

- [Chakra UI](https://github.com/chakra-ui/chakra-ui/blob/master/CONTRIBUTING.md)
  by [Segun Adebayo](https://twitter.com/thesegunadebayo)

**Huge thanks 🙏:** to _above wonderful persons_ for creating awesome projects
which helped me build this project.
