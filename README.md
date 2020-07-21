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
    - [Tailwind Layout](#tailwind-layout)
      - [Container](#container)
      - [Box Sizing](#box-sizing)
      - [Display](#display)
      - [Float](#float)
      - [Clear](#clear)
      - [Clear](#clear-1)
      - [Object Fit](#object-fit)
      - [Object Position](#object-position)
      - [Overflow](#overflow)
      - [Position](#position)
      - [Top / Right / Bottom / Left](#top--right--bottom--left)
      - [Visibility](#visibility)
      - [Z-Index](#z-index)
    - [Tailwind FlexBox](#tailwind-flexbox)
      - [Flex Direction](#flex-direction)
      - [Flex Wrap](#flex-wrap)
      - [Align Items](#align-items)
      - [Align Content](#align-content)
      - [Align Self](#align-self)
      - [Justify Content](#justify-content)
      - [Flex](#flex)
      - [Flex Grow](#flex-grow)
      - [Flex Shrink](#flex-shrink)
      - [Flex Order](#flex-order)
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

### [Tailwind](https://tailwindcss.com/) Layout

#### [Container](https://tailwindcss.com/docs/container)

| Snippet     | Purpose                                                             |
| ----------- | ------------------------------------------------------------------- |
| `container` | A component for fixing an element's width to the current breakpoint |

#### [Box Sizing](https://tailwindcss.com/docs/box-sizing)

| Snippet       | Purpose                  |
| ------------- | ------------------------ |
| `box-border`  | box-sizing: border-box;  |
| `box-content` | box-sizing: content-box; |

#### [Display](https://tailwindcss.com/docs/display)

| Snippet              | Purpose                      |
| -------------------- | ---------------------------- |
| `hidden`             | display: none;               |
| `block`              | display: block;              |
| `flow-root`          | display: flow-root;          |
| `inline-block`       | display: inline-block;       |
| `inline`             | display: inline;             |
| `flex`               | display: flex;               |
| `inline-flex`        | display: inline-flex;        |
| `grid`               | display: grid;               |
| `inline-grid`        | display: inline-grid;        |
| `table`              | display: table;              |
| `table-caption`      | display: table-caption;      |
| `table-cell`         | display: table-cell;         |
| `table-column`       | display: table-column;       |
| `table-column-group` | display: table-column-group; |
| `table-footer-group` | display: table-footer-group; |
| `table-header-group` | display: table-header-group; |
| `table-row-group`    | display: table-row-group;    |
| `table-row`          | display: table-row;          |

#### [Float](https://tailwindcss.com/docs/float)

| Snippet       | Purpose                                                |
| ------------- | ------------------------------------------------------ |
| `float-right` | float: right;                                          |
| `float-left`  | float: left;                                           |
| `float-none`  | float: none;                                           |
| `clearfix`    | &::after { content: "": display: table; clear: both; } |

#### [Clear](https://tailwindcss.com/docs/clear)

| Snippet       | Purpose       |
| ------------- | ------------- |
| `clear-left`  | clear: left;  |
| `clear-right` | clear: right; |
| `clear-both`  | clear: both;  |
| `clear-none`  | clear: none;  |

#### [Clear](https://tailwindcss.com/docs/clear)

| Snippet       | Purpose       |
| ------------- | ------------- |
| `clear-left`  | clear: left;  |
| `clear-right` | clear: right; |
| `clear-both`  | clear: both;  |
| `clear-none`  | clear: none;  |

#### [Object Fit](https://tailwindcss.com/docs/object-fit)

| Snippet             | Purpose                 |
| ------------------- | ----------------------- |
| `object-contain`    | object-fit: contain;    |
| `object-cover`      | object-fit: cover;      |
| `object-fill`       | object-fit: fill;       |
| `object-none`       | object-fit: none;       |
| `object-scale-down` | object-fit: scale-down; |

#### [Object Position](https://tailwindcss.com/docs/object-position)

| Snippet               | Purpose                        |
| --------------------- | ------------------------------ |
| `object-bottom`       | object-position: bottom;       |
| `object-center`       | object-position: center;       |
| `object-left`         | object-position: left;         |
| `object-left-bottom`  | object-position: left bottom;  |
| `object-left-top`     | object-position: left top;     |
| `object-right`        | object-position: right;        |
| `object-right-bottom` | object-position: right bottom; |
| `object-right-top`    | object-position: right top;    |
| `object-top`          | object-position: top;          |

#### [Overflow](https://tailwindcss.com/docs/overflow)

| Snippet              | Purpose                            |
| -------------------- | ---------------------------------- |
| `overflow-auto`      | overflow: auto;                    |
| `overflow-hidden`    | overflow: hidden;                  |
| `overflow-visible`   | overflow: visible;                 |
| `overflow-scroll`    | overflow: scroll;                  |
| `overflow-x-auto`    | overflow-x: auto;                  |
| `overflow-y-auto`    | overflow-y: auto;                  |
| `overflow-x-hidden`  | overflow-x: hidden;                |
| `overflow-y-hidden`  | overflow-y: hidden;                |
| `overflow-x-visible` | overflow-x: visible;               |
| `overflow-y-visibl`  | overflow-y: visible;               |
| `overflow-x-scroll`  | overflow-x: scroll;                |
| `overflow-y-scroll`  | overflow-y: scroll;                |
| `scrolling-touch`    | -webkit-overflow-scrolling: touch; |
| `scrolling-auto`     | -webkit-overflow-scrolling: auto;  |

#### [Position](https://tailwindcss.com/docs/position)

| Snippet    | Purpose             |
| ---------- | ------------------- |
| `static`   | position: static;   |
| `fixed`    | position: fixed;    |
| `absolute` | position: absolute; |
| `relative` | position: relative; |
| `sticky`   | position: sticky;   |

#### [Top / Right / Bottom / Left](https://tailwindcss.com/docs/top-right-bottom-left)

| Snippet        | Purpose                                           |
| -------------- | ------------------------------------------------- |
| `inset-0`      | top: 0; right: 0; bottom: 0; left: 0;             |
| `inset-y-0`    | top: 0; bottom: 0;                                |
| `inset-x-0`    | right: 0; left: 0;                                |
| `top-0`        | top: 0;                                           |
| `right-0`      | right: 0;                                         |
| `bottom-0`     | bottom: 0;                                        |
| `left-0`       | left: 0;                                          |
| `inset-auto`   | top: auto; right: auto; bottom: auto; left: auto; |
| `inset-y-auto` | top: auto; bottom: auto;                          |
| `inset-x-auto` | left: auto; right: auto;                          |
| `top-auto`     | top: auto;                                        |
| `bottom-auto`  | bottom: auto;                                     |
| `left-auto`    | left: auto;                                       |
| `right-auto`   | right: auto;                                      |

#### [Visibility](https://tailwindcss.com/docs/visibility)

| Snippet     | Purpose              |
| ----------- | -------------------- |
| `visible`   | visibility: visible; |
| `invisible` | visibility: hidden;  |

#### [Z-Index](https://tailwindcss.com/docs/z-index)

| Snippet  | Purpose        |
| -------- | -------------- |
| `z-0`    | z-index: 0;    |
| `z-10`   | z-index: 10;   |
| `z-20`   | z-index: 20;   |
| `z-30`   | z-index: 30;   |
| `z-40`   | z-index: 40;   |
| `z-50`   | z-index: 50;   |
| `z-auto` | z-index: auto; |

### [Tailwind](https://tailwindcss.com/) FlexBox

#### [Flex Direction](https://tailwindcss.com/docs/flex-direction)

| Snippet            | Purpose                         |
| ------------------ | ------------------------------- |
| `flex-row`         | flex-direction: row;            |
| `flex-row-reverse` | flex-direction: row-reverse;    |
| `flex-col`         | flex-direction: column;         |
| `flex-col-reverse` | flex-direction: column-reverse; |

#### [Flex Wrap](https://tailwindcss.com/docs/flex-wrap)

| Snippet             | Purpose                  |
| ------------------- | ------------------------ |
| `flex-no-wrap`      | flex-wrap: nowrap;       |
| `flex-wrap`         | flex-wrap: wrap;         |
| `flex-wrap-reverse` | flex-wrap: wrap-reverse; |

#### [Align Items](https://tailwindcss.com/docs/align-items)

| Snippet          | Purpose                  |
| ---------------- | ------------------------ |
| `items-stretch`  | align-items: stretch;    |
| `items-start`    | align-items: flex-start; |
| `items-center`   | align-items: center;     |
| `items-end`      | align-items: flex-end;   |
| `items-baseline` | align-items: baseline;   |

#### [Align Content](https://tailwindcss.com/docs/align-content)

| Snippet           | Purpose                       |
| ----------------- | ----------------------------- |
| `content-start`   | align-content: flex-start;    |
| `content-center`  | align-content: center;        |
| `content-end`     | align-content: flex-end;      |
| `content-between` | align-content: space-between; |
| `content-around`  | align-content: space-around;  |

#### [Align Self](https://tailwindcss.com/docs/align-self)

| Snippet        | Purpose                 |
| -------------- | ----------------------- |
| `self-auto`    | align-self: auto;       |
| `self-start`   | align-self: flex-start; |
| `self-center`  | align-self: center;     |
| `self-end`     | align-self: flex-end;   |
| `self-stretch` | align-self: stretch;    |

#### [Justify Content](https://tailwindcss.com/docs/justify-content)

| Snippet           | Purpose                         |
| ----------------- | ------------------------------- |
| `justify-start`   | justify-content: flex-start;    |
| `justify-center`  | justify-content: center;        |
| `justify-end`     | justify-content: flex-end;      |
| `justify-between` | justify-content: space-between; |
| `justify-around`  | justify-content: space-around;  |

#### [Flex](https://tailwindcss.com/docs/flex)

| Snippet        | Purpose         |
| -------------- | --------------- |
| `flex-initial` | flex: 0 1 auto; |
| `flex-1`       | flex: 1 1 0%;   |
| `flex-auto`    | flex: 1 1 auto; |
| `flex-none`    | flex: none;     |

#### [Flex Grow](https://tailwindcss.com/docs/flex-grow)

| Snippet       | Purpose       |
| ------------- | ------------- |
| `flex-grow`   | flex-grow: 1; |
| `flex-grow-0` | flex-grow: 0; |

#### [Flex Shrink](https://tailwindcss.com/docs/flex-shrink)

| Snippet         | Purpose         |
| --------------- | --------------- |
| `flex-shrink`   | flex-shrink: 1; |
| `flex-shrink-0` | flex-shrink: 0; |

#### [Flex Order](https://tailwindcss.com/docs/order)

| Snippet       | Purpose       |
| ------------- | ------------- |
| `order-first` | order: -9999; |
| `order-last`  | order: 9999;  |
| `order-none`  | order: 0;     |
| `order-1`     | order: 1;     |
| `order-2`     | order: 2;     |
| `order-3`     | order: 3;     |
| `order-4`     | order: 4;     |
| `order-5`     | order: 5;     |
| `order-6`     | order: 6;     |
| `order-7`     | order: 7;     |
| `order-8`     | order: 8;     |
| `order-9`     | order: 9;     |
| `order-10`    | order: 10;    |
| `order-11`    | order: 11;    |
| `order-12`    | order: 12;    |

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
