<p align="center">
  <h2 align="center">npm-ts-starter</h1>
</p>

# Usage

1. Clone this repo:

   ```
     git clone git@github.com:vriad/npm-ts-starter.git yourpkgname
     cd yourpkgname
   ```

   Then create a new repoisitory in your GitHub account and set it up

   ```
   rm -rf .git
   git init
   git remote add origin GITHUB_REMOTE_URL
   git add .
   git commit -am "Initial commit"
   git push origin master
   ```

2. In package.json: update "name", "description", "repository", "keywords", "tags", "hompage", and any other relevant fields.
3. Implement your module! Start writing code in index.ts.
4. Write tests! See '**tests**/sample.ts' for some basic examples. We use Jest as a test runner; check out the documenation at https://jestjs.io. Run your tests with `yarn test`. This automatically generates a badge like this to display your test coverage: [![coverage](./coverage.svg)](./src/__tests__)
5. Write a README. An initial template is below. Find and replace all references to "pkgname" with your package's name and "username" with your GitHub username. Delete this "Meta-README" section before you deploy (everything above the red line).
6. Install Node ([here](https://nodejs.org/en/)) if you haven't already. This automatically installs the `npm` command-line tool to your computer.
7. Create an npm account through npmjs.com.
8. Use the `npm login` command to sign into npm on your computer.
9. Build your project with `yarn build`. This transpiles your TyeScript to JavaScript code and writes the output into `/lib`.
10. Publish to npm with `npm publish`.

<hr style="border-color:red" />

<p align="center">
  <h1 align="center">Sample NPM Package</h1>
</p>

<div style="display:flex;flex-direction:row;justify-content:center;flex-wrap:wrap;">

<!-- Some of these badges will say "repo not found" until you publish to npm for the first time. -->

[![License][license-image]][license-url]
[![npm](https://img.shields.io/npm/dw/pkgname.svg)](https://www.npmjs.com/package/pkgname)
[![stars](https://img.shields.io/github/stars/username/pkgname)](https://img.shields.io/github/stars/username/pkgname)
[![coverage](./coverage.svg)](./src/__tests__)

</div>

[license-url]: https://opensource.org/licenses/MIT
[license-image]: https://img.shields.io/github/license/username/pkgname

<br/>

#### Table of contents

- [Installation](#installation)

# Installation

To install the latest version:

```sh
npm install --save pkgname
```

```sh
yarn add pkgname
```

#### TypeScript versions

Compatible with TypeScript 3.2+.

# Usage

Write stuff here!

# Changelog

| version     | release notes   |
| ----------- | --------------- |
| pkgname@1.0 | Initial release |
