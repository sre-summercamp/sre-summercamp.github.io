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

### 3. Build the theme

You'll need `npm` installed on your computer

```shell
pushd themes/devfest-theme-hugo
npm install
npm run build
popd
```
This step will be probably removed and replaced by compiled version of this theme.

### 4. Start the Hugo server

Run the server:

```shell
hugo server -D
```
Navigate to the site at http://localhost:1313/.

### 5. Deploy changes

Changes are deployed using Github Actions this [workflow](.github/workflows/gh-pages.yml),
so you just need to open and merge a pull request to publish new changes.
