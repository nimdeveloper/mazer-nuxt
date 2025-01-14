<div align="center">

# Mazer Nuxt

</div>

<div align="center">

[![All Contributors](https://img.shields.io/github/contributors/bl0cknumber/mazer-nuxt)](https://github.com/zuramai/mazer/graphs/contributors)
![GitHub last commit](https://img.shields.io/github/last-commit/bl0cknumber/mazer-nuxt.svg)
![GitHub repo size in bytes](https://img.shields.io/github/repo-size/badges/shields.svg)
[![License](https://img.shields.io/github/license/bl0cknumber/mazer-nuxt.svg)](LICENSE)
[![Known Vulnerabilities](https://snyk.io/test/github/fzn0x/mazer-nuxt/badge.svg?targetFile=package.json)](https://snyk.io/test/github/fzn0x/mazer-nuxt?targetFile=package.json)

</div>

<p align="center">
  <a href="https://github.com/zuramai/mazer">Mazer</a> is an Admin Dashboard Template that can help you develop faster. Made with Bootstrap 5. No jQuery dependency.
</p>

## Table of contents

- [Installation Guide](#installation-guide)
- [Contributing](#contributing)
- [License](#license)

## Warnings

##### How to fix Deprecation Warning: $weight: Passing a number without unit % (100) is deprecated. ?

This is issue caused by latest bootstrap (5.2.2), please wait for bootstrap 5.3.0

##### How to fix peer dependencies issues warning?

- remove node_modules
- remove pnpm-lock.yaml
- create .npmrc with `auto-install-peers` enabled (this step is already provided by Mazer Nuxt)
- pnpm install --shamefully-hoist 

## Installation Guide

You may need to use Node.js v16.9.0 or above to continue with Mazer Nuxt installation guide.
## Build Setup

```bash
# clone the repository
$ git clone https://github.com/fauzan121002/mazer-nuxt.git

# navigate to the folder
$ cd mazer-nuxt
```

After clone the repository and navigate to the folder, you can use few commands below

```bash
# enable corepack
$ corepack enable

# install dependencies
# please use the --shamefully-hoist parameter 
$ pnpm install --shamefully-hoist 

# serve with hot reload at localhost:3000
$ pnpm run dev

# build for production and launch server
$ pnpm run build
$ pnpm run start

# generate static project
$ pnpm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Contributing

See Contributing Guide [here](./CONTRIBUTING.md)

## License

Mazer Nuxt is under MIT License.
