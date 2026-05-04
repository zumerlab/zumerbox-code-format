# @zumerbox/code-format

> [!WARNING]
> **DEPRECATED.** Replaced by [`@zumerbox/lint-preset`](https://github.com/zumerlab/zumerbox-lint-preset). Use the `format` binary in that package.

This tool is designed to facilitate code formatting using Prettier, a popular code formatting tool. It checks the formatting of JavaScript, HTML, and Markdown files within specified directories and their subdirectories.


Refer to the [ZumerBox bundle](https://github.com/zumerlab/zumerbox) for more information and tools.


## Installation

```bash
npm install @zumerbox/code-format --save-dev
```

## Usage

```bash
npx @zumerbox/code-format
```

## Options

By default Prettier is instructed to perform a check without making any changes to the files. To fix any formatting issues run `@zumerbox/code-format` again with the `--write` argument to fix code style.

## Credits

This tool is powered by Prettier (https://prettier.io)
