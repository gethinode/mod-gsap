# Hinode Module - GSAP

<!-- Tagline -->
<p align="center">
    <b>A Hugo module to add GSAP animations to your Hinode site</b>
    <br />
</p>

<!-- Badges -->
<p align="center">
    <a href="https://gohugo.io" alt="Hugo website">
        <img src="https://img.shields.io/badge/generator-hugo-brightgreen">
    </a>
    <a href="https://gethinode.com" alt="Hinode theme">
        <img src="https://img.shields.io/badge/theme-hinode-blue">
    </a>
    <a href="https://github.com/gethinode/mod-gsap/commits/main" alt="Last commit">
        <img src="https://img.shields.io/github/last-commit/gethinode/mod-gsap.svg">
    </a>
    <a href="https://github.com/gethinode/mod-gsap/issues" alt="Issues">
        <img src="https://img.shields.io/github/issues/gethinode/mod-gsap.svg">
    </a>
    <a href="https://github.com/gethinode/mod-gsap/pulls" alt="Pulls">
        <img src="https://img.shields.io/github/issues-pr-raw/gethinode/mod-gsap.svg">
    </a>
    <a href="https://github.com/gethinode/mod-gsap/blob/main/LICENSE" alt="License">
        <img src="https://img.shields.io/github/license/gethinode/mod-gsap">
    </a>
</p>

## About

![Logo](https://raw.githubusercontent.com/gethinode/hinode/main/static/img/logo.png)

Hinode is a clean blog theme for [Hugo][hugo], an open-source static site generator. Hinode is available as a [template][repository_template], and a [main theme][repository]. This repository maintains a Hugo module to add [GSAP][gsap] animations to a Hinode site. Visit the Hinode documentation site for [installation instructions][hinode_docs].

## Notes

This modules exposes only one of the GSAP plugins (ScrollTrigger) by default. All extensions provided by GSAP are available in the `dist` folder. Override or modify the mount configuration in `config.toml` as needed. Register the plugins by adding them to the function `gsap.registerPlugin` in the file `assets/js/modules/gsap/_init.js`.

## Contributing

This module uses [semantic-release][semantic-release] to automate the release of new versions. The package uses `husky` and `commitlint` to ensure commit messages adhere to the [Conventional Commits][conventionalcommits] specification. You can run `npx git-cz` from the terminal to help prepare the commit message.

<!-- MARKDOWN LINKS -->
[gsap]: https://gsap.com
[hugo]: https://gohugo.io
[hinode_docs]: https://gethinode.com
[repository]: https://github.com/gethinode/hinode.git
[repository_template]: https://github.com/gethinode/template.git
[conventionalcommits]: https://www.conventionalcommits.org
[husky]: https://typicode.github.io/husky/
[semantic-release]: https://semantic-release.gitbook.io/
