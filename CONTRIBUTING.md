# Welcome Aboard

Thanks for showing interest in contributing to VSCode CSS Snippets 💖

## Introduction

Valid snippets require below 4 details,

1. **Snippet Name** - A unique name to differentiate from other snippets
2. **Prefix** - Trigger word for IntelliSense
3. **Body** - Actula snippet as array of strings, each one will be displayed in
   a new line
4. **Description** - Brief info about the snippets

**Example:**

```json
{
  "container": {
    "prefix": "container",
    "body": [".container {", "  width: 100%;", "}", ""],
    "description": "A component for fixing an element's width to the current breakpoint."
  }
}
```

[Detailed Snippet Explanation](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_create-your-own-snippets)

## Quick Contribution Details

Feel free to contact me via [Twitter](https://twitter.com/navin_moorthy), if you
need any help contributing.

If you are generous, consider helping me by following the docs from
[here](#detailed-contribution-details).

1. Copy your favourite line/lines of CSS,

   **Example:**

```css
.grid-center {
  display: grid;
  place-items: center;
}
```

2. Paste them in the [Snippet Generator APP](https://snippet-generator.app/) in
   the `body`(Your snippet...), fill the `description`(Desciption...) and
   `prefix`(Tab trigger...)
3. Copy the snippet output from the app.
4. Go the Github →
   [`snippet.json`](https://github.com/navin-moorthy/vscode-css-snippets/blob/master/snippets/contributions/snippet.json)
5. Click `Edit this file` - pen icon.
6. Paste the copied snippet inside the curly braces.
7. Submit by clicking `Propose changes` button in the bottom of the page.
8. This will create a fork of my repo to your repos, so you can create a pull
   request to my repo.

## Detailed Contribution Details

The following steps will get you setup to contribute changes to this repo:

### Setup

1. Fork the repo (click the <kbd>Fork</kbd> button at the top right of
   [this page](https://github.com/navin-moorthy/vscode-css-snippets))

2. Clone your fork locally

```shell
# in a terminal, cd to parent directory where you want your clone to be, then
git clone https://github.com/<your_github_username>/vscode-css-snippets.git
```

cd vscode-css-snippets

Uses `yarn` mostly and `lerna` just for `github releases`

### Development

#### What's in the folder

- This folder contains all of the files necessary for your extension.
- `package.json` - this is the manifest file that defines the location of each
  snippet file and specifies the language of the snippets
  `contributes.snippets`.
- `snippets/` - the folder containing all snippets.

#### Creating new snippets

- New snippets can be created by following the first 3 steps from
  [here](#quick-contribution-details)
- You can utilize
  [snippet variables](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_variables)
  to enable interactivity within you snippets
- Check
  [`snippets/breakpoints.json`](https://github.com/navin-moorthy/vscode-css-snippets/blob/master/snippets/contributions/snippet.json)

#### Test your snippets locally

- Press `F5` to open a new window with your extension loaded.
- Create a new file with a file name suffix matching your language.
- Verify that your snippets are proposed on intellisense.

#### Make changes and reload

- You can relaunch the extension from the debug toolbar after making changes to
  the files listed above.
- You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your
  extension to load your changes.

> **🚨Proceed after testing your snippets inside debug window 🚨**

### Commit Convention

Commits should comply with the commit conventions used in this repository.

Commit using `yarn commit`, make sure to `yarn install` before running this
command.

> `yarn commit` is powered by [gacp](https://github.com/vivaxy/gacp) which
> follows with [Conventional Commits](https://www.conventionalcommits.org/) and
> [Gitmoji](https://gitmoji.carloscuesta.me/).

When you create a commit we kindly ask you to follow the convention
`category(scope or module): <emoji> message` in your commit message while using
one of the following categories:

Add new snippets under `feat` category,

- `feat / feature`: all changes that introduce completely new code or new
  features

Rest can be used when needed,

- `fix`: changes that fix a bug (ideally you will addtionally reference an issue
  if present)
- `refactor`: any code related change that is not a fix nor a feature
- `docs`: changing existing or creating new documentation (i.e. README, docs for
  usage of a lib or cli usage)
- `build`: all changes regarding the build of the software, changes to
  dependencies or the addition of new dependencies
- `style`: changes that do not affect the meaning of the code (white-space,
  formatting, missing semi-colons, etc)
- `perf`: A code change that improves performance
- `test`: all changes regarding tests (adding new tests or changing existing
  ones)
- `ci`: all changes regarding the configuration of continous integration (i.e.
  github actions, ci system)
- `chore`: all changes to the repository that do not fit into any of the above
  categories
- `revert`: reverts a previous commit

If you are interested in the detailed specification you can visit
[Conventional Commits](https://www.conventionalcommits.org/) or check out the
[Angular Commit Message Guidelines](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines)

### Steps to PR

Pull requests will be merged by me(@navin-moorthy) once submitted.

- Create a new branch out of the `master` branch.
- Commit your changes and push your branch with changes.
- Visit the [repo](https://github.com/navin-moorthy/vscode-css-snippets/) to get
  a prompt to submit a PR or create a PR manually.

[Example PR](https://github.com/navin-moorthy/vscode-css-snippets/pull/8)

## License

By contributing your code to the chakra-ui GitHub repository, you agree to
license your contribution under the
[MIT license](https://github.com/navin-moorthy/vscode-css-snippets/blob/master/LICENSE).
