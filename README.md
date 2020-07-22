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
    - [Tailwind Grid](#tailwind-grid)
      - [Grid Template Columns](#grid-template-columns)
      - [Grid Column Start / End](#grid-column-start--end)
      - [Grid Template Rows](#grid-template-rows)
      - [Grid Row Start / End](#grid-row-start--end)
      - [Gap](#gap)
      - [Grid Auto Flow](#grid-auto-flow)
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

### [Tailwind](https://tailwindcss.com/) Grid

#### [Grid Template Columns](https://tailwindcss.com/docs/grid-template-columns)

| Snippet          | Purpose                                            |
| ---------------- | -------------------------------------------------- |
| `grid-cols-1`    | grid-template-columns: repeat(1, minmax(0, 1fr));  |
| `grid-cols-2`    | grid-template-columns: repeat(2, minmax(0, 1fr));  |
| `grid-cols-3`    | grid-template-columns: repeat(3, minmax(0, 1fr));  |
| `grid-cols-4`    | grid-template-columns: repeat(4, minmax(0, 1fr));  |
| `grid-cols-5`    | grid-template-columns: repeat(5, minmax(0, 1fr));  |
| `grid-cols-6`    | grid-template-columns: repeat(6, minmax(0, 1fr));  |
| `grid-cols-7`    | grid-template-columns: repeat(7, minmax(0, 1fr));  |
| `grid-cols-8`    | grid-template-columns: repeat(8, minmax(0, 1fr));  |
| `grid-cols-9`    | grid-template-columns: repeat(9, minmax(0, 1fr));  |
| `grid-cols-10`   | grid-template-columns: repeat(10, minmax(0, 1fr)); |
| `grid-cols-11`   | grid-template-columns: repeat(11, minmax(0, 1fr)); |
| `grid-cols-12`   | grid-template-columns: repeat(12, minmax(0, 1fr)); |
| `grid-cols-none` | grid-template-columns: none;                       |

#### [Grid Column Start / End](https://tailwindcss.com/docs/grid-column)

| Snippet          | Purpose                         |
| ---------------- | ------------------------------- |
| `col-auto`       | grid-column: auto;              |
| `col-span-1`     | grid-column: span 1 / span 1;   |
| `col-span-2`     | grid-column: span 2 / span 2;   |
| `col-span-3`     | grid-column: span 3 / span 3;   |
| `col-span-4`     | grid-column: span 4 / span 4;   |
| `col-span-5`     | grid-column: span 5 / span 5;   |
| `col-span-6`     | grid-column: span 6 / span 6;   |
| `col-span-7`     | grid-column: span 7 / span 7;   |
| `col-span-8`     | grid-column: span 8 / span 8;   |
| `col-span-9`     | grid-column: span 9 / span 9;   |
| `col-span-10`    | grid-column: span 10 / span 10; |
| `col-span-11`    | grid-column: span 11 / span 11; |
| `col-span-12`    | grid-column: span 12 / span 12; |
| `col-start-1`    | grid-column-start: 1;           |
| `col-start-2`    | grid-column-start: 2;           |
| `col-start-3`    | grid-column-start: 3;           |
| `col-start-4`    | grid-column-start: 4;           |
| `col-start-5`    | grid-column-start: 5;           |
| `col-start-6`    | grid-column-start: 6;           |
| `col-start-7`    | grid-column-start: 7;           |
| `col-start-8`    | grid-column-start: 8;           |
| `col-start-9`    | grid-column-start: 9;           |
| `col-start-10`   | grid-column-start: 10;          |
| `col-start-11`   | grid-column-start: 11;          |
| `col-start-12`   | grid-column-start: 12;          |
| `col-start-13`   | grid-column-start: 13;          |
| `col-start-auto` | grid-column-start: auto;        |
| `col-end-1`      | grid-column-end: 1;             |
| `col-end-2`      | grid-column-end: 2;             |
| `col-end-3`      | grid-column-end: 3;             |
| `col-end-4`      | grid-column-end: 4;             |
| `col-end-5`      | grid-column-end: 5;             |
| `col-end-6`      | grid-column-end: 6;             |
| `col-end-7`      | grid-column-end: 7;             |
| `col-end-8`      | grid-column-end: 8;             |
| `col-end-9`      | grid-column-end: 9;             |
| `col-end-10`     | grid-column-end: 10;            |
| `col-end-11`     | grid-column-end: 11;            |
| `col-end-12`     | grid-column-end: 12;            |
| `col-end-13`     | grid-column-end: 13;            |
| `col-end-auto`   | grid-column-end: auto;          |

#### [Grid Template Rows](https://tailwindcss.com/docs/grid-template-rows)

| Snippet          | Purpose                                        |
| ---------------- | ---------------------------------------------- |
| `grid-rows-1`    | grid-template-rows: repeat(1, minmax(0, 1fr)); |
| `grid-rows-2`    | grid-template-rows: repeat(2, minmax(0, 1fr)); |
| `grid-rows-3`    | grid-template-rows: repeat(3, minmax(0, 1fr)); |
| `grid-rows-4`    | grid-template-rows: repeat(4, minmax(0, 1fr)); |
| `grid-rows-5`    | grid-template-rows: repeat(5, minmax(0, 1fr)); |
| `grid-rows-6`    | grid-template-rows: repeat(6, minmax(0, 1fr)); |
| `grid-rows-none` | grid-template-rows: none;                      |

#### [Grid Row Start / End](https://tailwindcss.com/docs/grid-row)

| Snippet          | Purpose                    |
| ---------------- | -------------------------- |
| `row-auto`       | grid-row: auto;            |
| `row-span-1`     | grid-row: span 1 / span 1; |
| `row-span-2`     | grid-row: span 2 / span 2; |
| `row-span-3`     | grid-row: span 3 / span 3; |
| `row-span-4`     | grid-row: span 4 / span 4; |
| `row-span-5`     | grid-row: span 5 / span 5; |
| `row-span-6`     | grid-row: span 6 / span 6; |
| `row-start-1`    | grid-row-start: 1;         |
| `row-start-2`    | grid-row-start: 2;         |
| `row-start-3`    | grid-row-start: 3;         |
| `row-start-4`    | grid-row-start: 4;         |
| `row-start-5`    | grid-row-start: 5;         |
| `row-start-6`    | grid-row-start: 6;         |
| `row-start-7`    | grid-row-start: 7;         |
| `row-start-auto` | grid-row-start: auto;      |
| `row-end-1`      | grid-row-end: 1;           |
| `row-end-2`      | grid-row-end: 2;           |
| `row-end-3`      | grid-row-end: 3;           |
| `row-end-4`      | grid-row-end: 4;           |
| `row-end-5`      | grid-row-end: 5;           |
| `row-end-6`      | grid-row-end: 6;           |
| `row-end-7`      | grid-row-end: 7;           |
| `row-end-auto`   | grid-row-end: auto;        |

#### [Gap](https://tailwindcss.com/docs/gap)

| Snippet      | Purpose              |
| ------------ | -------------------- |
| `gap-0`      | gap: 0;              |
| `gap-1`      | gap: 0.25rem;        |
| `gap-2`      | gap: 0.5rem;         |
| `gap-3`      | gap: 0.75rem;        |
| `gap-4`      | gap: 1rem;           |
| `gap-5`      | gap: 1.25rem;        |
| `gap-6`      | gap: 1.5rem;         |
| `gap-8`      | gap: 2rem;           |
| `gap-10`     | gap: 2.5rem;         |
| `gap-12`     | gap: 3rem;           |
| `gap-16`     | gap: 4rem;           |
| `gap-20`     | gap: 5rem;           |
| `gap-24`     | gap: 6rem;           |
| `gap-32`     | gap: 8rem;           |
| `gap-40`     | gap: 10rem;          |
| `gap-48`     | gap: 12rem;          |
| `gap-56`     | gap: 14rem;          |
| `gap-64`     | gap: 16rem;          |
| `gap-px`     | gap: 1px;            |
| `row-gap-0`  | row-gap: 0;          |
| `row-gap-1`  | row-gap: 0.25rem;    |
| `row-gap-2`  | row-gap: 0.5rem;     |
| `row-gap-3`  | row-gap: 0.75rem;    |
| `row-gap-4`  | row-gap: 1rem;       |
| `row-gap-5`  | row-gap: 1.25rem;    |
| `row-gap-6`  | row-gap: 1.5rem;     |
| `row-gap-8`  | row-gap: 2rem;       |
| `row-gap-10` | row-gap: 2.5rem;     |
| `row-gap-12` | row-gap: 3rem;       |
| `row-gap-16` | row-gap: 4rem;       |
| `row-gap-20` | row-gap: 5rem;       |
| `row-gap-24` | row-gap: 6rem;       |
| `row-gap-32` | row-gap: 8rem;       |
| `row-gap-40` | row-gap: 10rem;      |
| `row-gap-48` | row-gap: 12rem;      |
| `row-gap-56` | row-gap: 14rem;      |
| `row-gap-64` | row-gap: 16rem;      |
| `row-gap-px` | row-gap: 1px;        |
| `col-gap-0`  | column-gap: 0;       |
| `col-gap-1`  | column-gap: 0.25rem; |
| `col-gap-2`  | column-gap: 0.5rem;  |
| `col-gap-3`  | column-gap: 0.75rem; |
| `col-gap-4`  | column-gap: 1rem;    |
| `col-gap-5`  | column-gap: 1.25rem; |
| `col-gap-6`  | column-gap: 1.5rem;  |
| `col-gap-8`  | column-gap: 2rem;    |
| `col-gap-10` | column-gap: 2.5rem;  |
| `col-gap-12` | column-gap: 3rem;    |
| `col-gap-16` | column-gap: 4rem;    |
| `col-gap-20` | column-gap: 5rem;    |
| `col-gap-24` | column-gap: 6rem;    |
| `col-gap-32` | column-gap: 8rem;    |
| `col-gap-40` | column-gap: 10rem;   |
| `col-gap-48` | column-gap: 12rem;   |
| `col-gap-56` | column-gap: 14rem;   |
| `col-gap-64` | column-gap: 16rem;   |
| `col-gap-px` | column-gap: 1px;     |

#### [Grid Auto Flow](https://tailwindcss.com/docs/grid-auto-flow)

| Snippet               | Purpose                       |
| --------------------- | ----------------------------- |
| `grid-flow-row`       | grid-auto-flow: row;          |
| `grid-flow-col`       | grid-auto-flow: column;       |
| `grid-flow-row-dense` | grid-auto-flow: row dense;    |
| `grid-flow-col-dense` | grid-auto-flow: column dense; |

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
