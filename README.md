<a name="readme-top"></a><div align="center">



<h1>garron Lint</h1>

ESlint 配置、Prettier 配置、Remark 配置

[Changelog](./CHANGELOG.md)



</div>

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<details>
<summary><kbd>Table of contents</kbd></summary>

#### TOC

- [📦 安装](#-installation)
- [使用方法](#-usage)
  - [.npmrc](#npmrc)
  - [ESlint](#eslint)
  - [Stylelint](#stylelint)
  - [Commitlint](#commitlint)
  - [更新日志](#changelog)
  - [Prettier](#prettier)
  - [Semantic Release](#semantic-release)
- [⌨️ 本地开发](#️-local-development)
- [🤝 贡献](#-contributing)

####

</details>

## 📦 安装

要安装  garron Lint, 请运行以下命令:


```bash
$ bun add @garron/lint -D
```


<div align="right">

[back-to-top](#readme-top)

</div>

## 用法

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

配置可以在以下位置找到 [`.eslintrc.js`](/src/eslint/index.ts)

```js
module.exports = require('@garron/lint').eslint;
```

### Stylelint

配置可以在以下位置找到 [`.stylelintrc.js`](/src/stylelint/index.ts)

```js
module.exports = require('@garron/lint').stylelint;
```

### Commitlint

配置可以在以下位置找到 [`.commitlintrc.js`](/src/commitlint/index.ts)

```js
module.exports = require('@garron/lint').commitlint;
```

### Changelog

配置可以在以下位置找到 [`.changelogrc.js`](/src/changelog/index.ts)

```js
module.exports = require('@garron/lint').changelog;
```

### Remark

配置可以在以下位置找到 [`.remarkrc.js`](/src/remarklint/index.ts)

```js
module.exports = require('@garron/lint').remarklint;
```

### Prettier

配置可以在以下位置找到 [`.prettierrc.js`](/src/prettier/index.ts)

```js
module.exports = require('@garron/lint').prettier;
```

### Semantic Release

配置可以在以下位置找到 [`.releaserc.js`](/src/semantic-release/index.ts)

```js
module.exports = require('@garron/lint').semanticRelease;
```

<div align="right">

[back-to-top](#readme-top)

</div>

## ⌨️ 本地开发


```bash
$ git clone https://github.com/geallenboy/garron-lint.git
$ cd garron/lint
$ bun install
$ bun start
```

<div align="right">

[back-to-top](#readme-top)

</div>



#### 📝 许可证

Copyright © 2024 [garron]. <br />
This project is [MIT](./LICENSE) licensed.

