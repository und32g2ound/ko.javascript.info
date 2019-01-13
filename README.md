# The JavaScript Tutorial

This repository hosts the content of the Modern JavaScript Tutorial, published at [https://javascript.info](https://javascript.info).

## Translations

(In alphabetical order):

| Language | Github | Translation leads | Translated (%) | Last&nbsp;Commit | Published |
|----------|--------|-------------------|----------------|-------------|-----------|
| Chinese | [xitu/javascript-tutorial-zh](https://github.com/xitu/javascript-tutorial-zh) | @leviding | ![](http://translate-hook.javascript.info/stats/zh.svg) | ![](https://img.shields.io/github/last-commit/xitu/javascript-tutorial-zh.svg?maxAge=3600&link=https://github.com/xitu/javascript-tutorial-zh) | https://zh.javascript.info |
| Japanese | [KenjiI/javascript-tutorial-ja](https://github.com/KenjiI/javascript-tutorial-ja) | @KenjiI | ![](http://translate-hook.javascript.info/stats/ja.svg) | ![](https://img.shields.io/github/last-commit/KenjiI/javascript-tutorial-ja.svg?maxAge=3600) | https://ja.javascript.info |
| Polish | [krzmaciek/javascript-tutorial-pl](https://github.com/krzmaciek/javascript-tutorial-pl) | @krzmaciek | ![](http://translate-hook.javascript.info/stats/pl.svg) | ![](https://img.shields.io/github/last-commit/krzmaciek/javascript-tutorial-pl.svg?maxAge=3600) |  |
| Romanian | [lighthousand/javascript-tutorial-ro](https://github.com/lighthousand/javascript-tutorial-ro) | @lighthousand | started | ![](https://img.shields.io/github/last-commit/lighthousand/javascript-tutorial-ro.svg?maxAge=3600) |  |
| Russian | [iliakan/javascript-tutorial-ru](https://github.com/iliakan/javascript-tutorial-ru) | @iliakan | ![] | * | (https://img.shields.io/github/last-commit/iliakan/javascript-tutorial-ru.svg?maxAge=3600) | https://learn.javascript.ru |
| Turkish | [sahinyanlik/javascript-tutorial-tr](https://github.com/sahinyanlik/javascript-tutorial-tr) | @sahinyanlik | ![](http://translate-hook.javascript.info/stats/tr.svg) | ![](https://img.shields.io/github/last-commit/sahinyanlik/javascript-tutorial-tr.svg?maxAge=3600) | |



`*` – the previous version is published in Russian, need to backport/translate the new one from English.

If you'd like to translate it into your language, please clone the repository, change its name to `javascript-tutorial-...` (by the language) and [create an issue](https://github.com/iliakan/javascript-tutoria-en/issues/new) for me to add you to the list.

You can edit the text in any editor (markdown-like syntax). The server to run the tutorial locally and see how it looks is at <https://github.com/iliakan/javascript-tutorial-server>.  



## Structure

Every chapter, article or a task has its folder.

The folder is named like `N-url`, where `N` is a number for the sorting purposes and `url` is the URL part with title of the material.

The type of the material is defined by the file inside the folder:

  - `index.md` stands for a chapter
  - `article.md` stands for an article
  - `task.md` stands for a task (solution must be provided in `solution.md` file aswell)

Each of these files starts from the `# Main header`.
