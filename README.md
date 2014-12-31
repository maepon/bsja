# [Bootstrap](http://getbootstrap.com)
![Bower version](https://img.shields.io/bower/v/bootstrap.svg?style=flat)
[![npm version](https://img.shields.io/npm/v/bootstrap.svg?style=flat)](https://www.npmjs.com/package/bootstrap)
[![Build Status](https://img.shields.io/travis/twbs/bootstrap/master.svg?style=flat)](https://travis-ci.org/twbs/bootstrap)
[![devDependency Status](https://img.shields.io/david/dev/twbs/bootstrap.svg?style=flat)](https://david-dm.org/twbs/bootstrap#info=devDependencies)
[![Selenium Test Status](https://saucelabs.com/browser-matrix/bootstrap.svg)](https://saucelabs.com/u/bootstrap)

Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development, created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thornton](https://twitter.com/fat), and maintained by the [core team](https://github.com/orgs/twbs/people) with the massive support and involvement of the community.

Bootstrapは、Web制作をより早く、より簡単にするための、スマートで、直感的で協力なフロントエンドフレームワークです。[Mark Otto](https://twitter.com/mdo) と [Jacob Thornton](https://twitter.com/fat)が作成し、充実したサポートとコミュニティとの密接な連携を提供する[core team](https://github.com/orgs/twbs/people)によりメンテナンスされています。

To get started, check out <http://getbootstrap.com>!

<http://getbootstrap.com> をチェックして始めましょう！

## Table of contents

## 目次

- [Quick start](#quick-start)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Community](#community)
- [Versioning](#versioning)
- [Creators](#creators)
- [Copyright and license](#copyright-and-license)

- [クイックスタート](#quick-start)
- [バグや機能拡張の要求について](#bugs-and-feature-requests)
- [ドキュメントについて](#documentation)
- [貢献について](#contributing)
- [コミュニティについて](#community)
- [バージョン番号について](#versioning)
- [製作者について](#creators)
- [著作権とライセンス](#copyright-and-license)

## クイックスタート

Four quick start options are available:

手早く始めるには4つの方法があります:

- [Download the latest release](https://github.com/twbs/bootstrap/archive/v3.3.1.zip).
- Clone the repo: `git clone https://github.com/twbs/bootstrap.git`.
- Install with [Bower](http://bower.io): `bower install bootstrap`.
- Install with [npm](https://www.npmjs.org): `npm install bootstrap`.

- [最新リリースのダウンロード](https://github.com/twbs/bootstrap/archive/v3.3.1.zip).
- リポジトリのclone: `git clone https://github.com/twbs/bootstrap.git`.
- [Bower](http://bower.io)でのインストール: `bower install bootstrap`.
- [npm](https://www.npmjs.org)でのいんすとーる: `npm install bootstrap`.

Read the [Getting started page](http://getbootstrap.com/getting-started/) for information on the framework contents, templates and examples, and more.

フレームワークの内容、テンプレート、事例やその他の情報については、[Getting started page](http://getbootstrap.com/getting-started/)を読んでください。

### What's included

### 含まれている内容

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

ダウンロードしたデーターの中に下記の分類した共有のアセットと、コンプパイルしたものとミニファイされたバリエーションのディレクトリとファイルが含まれています。一部は下記のような感じです:

```
bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap-theme.css
│   ├── bootstrap-theme.css.map
│   └── bootstrap-theme.min.css
├── js/
│   ├── bootstrap.js
│   └── bootstrap.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2
```

We provide compiled CSS and JS (`bootstrap.*`), as well as compiled and minified CSS and JS (`bootstrap.min.*`). CSS [source maps](https://developers.google.com/chrome-developer-tools/docs/css-preprocessors) (`bootstrap.*.map`) are available for use with certain browsers' developer tools. Fonts from Glyphicons are included, as is the optional Bootstrap theme.

コンパイルされたCSSとJS(`bootstrap.*`)と同様にコンパイル後にミニファイされたCSSとJS(`bootstrap.min.*`)を提供しています。CSSの[source maps](https://developers.google.com/chrome-developer-tools/docs/css-preprocessors) (`bootstrap.*.map`)は対応しているブラウザのデベロッパーツールに向けて提供されています。Bootstrapテーマの付属品としてGlyphiconsのフォントが含まれています。

## バグや機能拡張の要求について

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/twbs/bootstrap/issues/new).

バグや機能追加の要望がありますか？まずは[issue guidelines](https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md#using-the-issue-tracker)を読んで、現在進行しているものや終了したイシューを検索してください。もし、あなたの把握しているバグや新しい機能のアイデアがまだ登録されていない場合は、[新しいイシューを開いでください](https://github.com/twbs/bootstrap/issues/new)。

## Documentation

Bootstrap's documentation, included in this repo in the root directory, is built with [Jekyll](http://jekyllrb.com) and publicly hosted on GitHub Pages at <http://getbootstrap.com>. The docs may also be run locally.

### Running documentation locally

1. If necessary, [install Jekyll](http://jekyllrb.com/docs/installation) (requires v2.5.x).
  - **Windows users:** Read [this unofficial guide](http://jekyll-windows.juthilo.com/) to get Jekyll up and running without problems.
2. Install the Ruby-based syntax highlighter, [Rouge](https://github.com/jneen/rouge), with `gem install rouge`.
3. From the root `/bootstrap` directory, run `jekyll serve` in the command line.
4. Open <http://localhost:9001> in your browser, and voilà.

Learn more about using Jekyll by reading its [documentation](http://jekyllrb.com/docs/home/).

### Documentation for previous releases

Documentation for v2.3.2 has been made available for the time being at <http://getbootstrap.com/2.3.2/> while folks transition to Bootstrap 3.

[Previous releases](https://github.com/twbs/bootstrap/releases) and their documentation are also available for download.



## Contributing

Please read through our [contributing guidelines](https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, if your pull request contains JavaScript patches or features, you must include relevant unit tests. All HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Mark Otto](https://github.com/mdo).

Editor preferences are available in the [editor config](https://github.com/twbs/bootstrap/blob/master/.editorconfig) for easy use in common text editors. Read more and download plugins at <http://editorconfig.org>.



## Community

Keep track of development and community news.

- Follow [@twbootstrap on Twitter](https://twitter.com/twbootstrap).
- Read and subscribe to [The Official Bootstrap Blog](http://blog.getbootstrap.com).
- Chat with fellow Bootstrappers in IRC. On the `irc.freenode.net` server, in the `##bootstrap` channel.
- Implementation help may be found at Stack Overflow (tagged [`twitter-bootstrap-3`](http://stackoverflow.com/questions/tagged/twitter-bootstrap-3)).



## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under [the Semantic Versioning guidelines](http://semver.org/). Sometimes we screw up, but we'll adhere to those rules whenever possible.



## Creators

**Mark Otto**

- <https://twitter.com/mdo>
- <https://github.com/mdo>

**Jacob Thornton**

- <https://twitter.com/fat>
- <https://github.com/fat>



## Copyright and license

Code and documentation copyright 2011-2014 Twitter, Inc. Code released under [the MIT license](https://github.com/twbs/bootstrap/blob/master/LICENSE). Docs released under [Creative Commons](https://github.com/twbs/bootstrap/blob/master/docs/LICENSE).
