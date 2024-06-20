<a name="readme-top"></a><div align="center">



<h1>garron Lint</h1>

ESlint config, Prettier config, Remark config for garron

[Changelog](./CHANGELOG.md) · [Report Bug][issues-link] · [Request Feature][issues-link]



</div>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<details>
<summary><kbd>Table of contents</kbd></summary>

#### TOC

- [📦 Installation](#-installation)
- [🤯 Usage](#-usage)
  - [.npmrc](#npmrc)
  - [ESlint](#eslint)
  - [Stylelint](#stylelint)
  - [Commitlint](#commitlint)
  - [Changelog](#changelog)
  - [Remark](#remark)
  - [Prettier](#prettier)
  - [Semantic Release](#semantic-release)
- [⌨️ Local Development](#️-local-development)
- [🤝 Contributing](#-contributing)

####

</details>

## 📦 Installation

To install garron Lint, run the following command:

[![][bun-shield]][bun-link]

```bash
$ bun add @garron/lint -D
```


<div align="right">

[![][back-to-top]](#readme-top)

</div>

## Usage

### .npmrc

```text
public-hoist-pattern[]=*@umijs/lint*
public-hoist-pattern[]=*changelog*
public-hoist-pattern[]=*commitlint*
public-hoist-pattern[]=*eslint*
public-hoist-pattern[]=*postcss*
public-hoist-pattern[]=*prettier*
public-hoist-pattern[]=*remark*
public-hoist-pattern[]=*semantic-release*
public-hoist-pattern[]=*stylelint*
```

### ESlint

config can be found at [`.eslintrc.js`](/src/eslint/index.ts)

```js
module.exports = require('@garron/lint').eslint;
```

### Stylelint

config can be found at [`.stylelintrc.js`](/src/stylelint/index.ts)

```js
module.exports = require('@garron/lint').stylelint;
```

### Commitlint

config can be found at [`.commitlintrc.js`](/src/commitlint/index.ts)

```js
module.exports = require('@garron/lint').commitlint;
```

### Changelog

config can be found at [`.changelogrc.js`](/src/changelog/index.ts)

```js
module.exports = require('@garron/lint').changelog;
```

### Remark

config can be found at [`.remarkrc.js`](/src/remarklint/index.ts)

```js
module.exports = require('@garron/lint').remarklint;
```

### Prettier

config can be found at [`.prettierrc.js`](/src/prettier/index.ts)

```js
module.exports = require('@garron/lint').prettier;
```

### Semantic Release

config can be found at [`.releaserc.js`](/src/semantic-release/index.ts)

```js
module.exports = require('@garron/lint').semanticRelease;
```

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## ⌨️ Local Development

You can use Github Codespaces for online development:

[![][codespaces-shield]][codespaces-link]

Or clone it for local development:

```bash
$ git clone https://github.com/geallenboy/garron-lint.git
$ cd garron/lint
$ bun install
$ bun start
```

<div align="right">

[![][back-to-top]](#readme-top)

</div>



#### 📝 License

Copyright © 2024 [garron][profile-link]. <br />
This project is [MIT](./LICENSE) licensed.

