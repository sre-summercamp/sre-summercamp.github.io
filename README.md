# SRE SummerCamp website

## Contribute

### 1. Install Hugo

This site is generated using the static site generator [Hugo](https://gohugo.io/).

Follow [these instructions](https://gohugo.io/getting-started/installing/) to install it on your computer.

### 2. Clone this repo

Clone this repo and its submodule using:

```shell
git clone --recurse-submodules git@github.com:sre-summercamp/sre-summercamp.github.io.git
```

### 3. Theme customization (optional)

If you want to customize the theme (CSS, JS, etc) you need to clone the repo
https://github.com/sre-summercamp/devfest-theme-hugo and build a new version
following its own instructions.

### 4. Start the Hugo server

Run the server:

```shell
hugo server -D
```
Navigate to the site at http://localhost:1313/.

### 5. Deploy changes

Changes are deployed using Github Actions this [workflow](.github/workflows/gh-pages.yml),
so you just need to open and merge a pull request to publish new changes.
