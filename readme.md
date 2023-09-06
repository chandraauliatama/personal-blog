# My Personal Blog Using Hugo

This repository is backup for my personal web using hugo

## Getting Started

To get started running the project locally, please follow the steps below.

First, clone the repository.

```bash
git clone git@github.com:chandraauliatama/personal-blog.git
```

Go to your blog directory.

```bash
cd personal-blog
```

Then, install hugo themes for this web, for this project I use themes called [INK](https://themes.gohugo.io/themes/hugo-ink/).

```bash
cd themes
git clone https://github.com/knadh/hugo-ink.git ink
```

Create git submodule for your actual web/blog

```bash
rm -rf public
git rm -r public
git submodule add -b master git@github.com:chandraauliatama/chandraauliatama.github.io.git public
```

To see your web/blog locally, run

```bash
hugo server -D
```

To build your web/blog, simply run

```bash
hugo
```

Finally, copy the address show in your terminal and open your browser.

## Technologies

- **[Hugo](https://gohugo.io/)**
- **[INK Themes](https://themes.gohugo.io/themes/hugo-ink/)**
