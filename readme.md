# My Personal Blog Using Hugo

This repository is backup for my personal web using hugo

## Getting Started

To get started running the project locally, please follow the steps below.

First, clone the repository.

```bash
git clone https://github.com/chandraauliatama/personal-blog.git
```

Then, install hugo themes for this web, for this project I use themes called [INK](https://themes.gohugo.io/themes/hugo-ink/).

```bash
cd personal-blog
cd themes
git clone https://github.com/knadh/hugo-ink.git ink
```

Create git submodule for your actual web/blog

```bash
cd personal-blog
rm -rf public
git rm -r public
git submodule add -b master git@github.com:chandraauliatama/chandraauliatama.github.io.git public
```

Start hugo server to see your web/blog locally

```bash
cd personal-blog
hugo server -D
```

Finally, copy the address show in your terminal and open your browser.

## Technologies

-   **[Hugo](https://gohugo.io/)**
-   **[INK Themes](https://themes.gohugo.io/themes/hugo-ink/)**
