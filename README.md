<p align="center">
	<a href="https://themes.gohugo.io/hugo-coder/">
		<img src="https://img.shields.io/badge/theme-hugo--coder-2b8cbe" alt="Hugo Theme Badge">
	</a>
	<a href="https://github.com/luizdepra/hugo-coder/blob/master/LICENSE.md">
		<img src="https://img.shields.io/github/license/luizdepra/hugo-coder.svg" alt="MIT License Badge">
	</a>
</p>

<p align="center">
	<a href="https://github.com/luizdepra/hugo-coder">
		<img src="images/logos/logotype-a.png" alt="Hugo Coder Logo" width="600px" height="184px">
	</a>
</p>

A simple and clean blog theme for [Hugo](https://gohugo.io/).

![](images/screenshot.png)

## About the fork

This fork was made because the original author of the project only visits the pull requests and issues every now and then.
I'm planning to contribute my modifications upstream so the users of the main project could benefit from them but in the meantime I can change the implementation without friction on this fork and share it with others.

### TODO

- [ ] Localization changes
    - [x] Update Hungarian translation
    - [ ] Update Hungarian date(/currency?) format(s)
- [ ] Mastodon cleanup
    - [x] Add possibility to link Mastodon posts per website posts
    - [ ] Add translatable partials (like "Comments") and other text
    - [ ] Fix '`disableComments` front matter variable is useless with Mastodon partial' bug
    - [ ] Make reply threads more structured (multiple/multi-level comments)
    - [ ] Add tickmark so the user can enable auto-loading comments
- [ ] Optimize site performance ([PageSpeed Insights](https://pagespeed.web.dev))

## Live Demo

See [here](https://hugo-coder.netlify.app/).

## Quick Start

1. Add the repository into your Hugo Project repository as a sub-module, `git submodule add https://github.com/luizdepra/hugo-coder.git themes/hugo-coder`.
2. Configure your `hugo.toml`. You can either use [this minimal configuration](https://github.com/luizdepra/hugo-coder/blob/main/docs/configurations.md#complete-example) as a base, or look for a complete explanation about all configurations [here](https://github.com/luizdepra/hugo-coder/blob/main/docs/configurations.md). The [`hugo.toml`](https://github.com/luizdepra/hugo-coder/blob/master/exampleSite/hugo.toml) inside the [`exampleSite`](https://github.com/luizdepra/hugo-coder/tree/master/exampleSite) is also a good reference.
3. Build your site with `hugo server` and see the result at `http://localhost:1313/`.

## Documentation

See the [`docs`](docs/home.md) folder.

## License

Coder is licensed under the [MIT license](https://github.com/luizdepra/hugo-coder/blob/master/LICENSE.md).

## Maintenance

This theme is maintained by its author [Luiz de Prá](https://github.com/luizdepra) with the help from these awesome [contributors](CONTRIBUTORS.md).

## Sponsoring

If you like my project or it was useful for you, consider supporting its development. Just:

<a href="https://www.buymeacoffee.com/luizdepra" target="_blank">
	<img src="https://cdn.buymeacoffee.com/buttons/default-green.png" alt="Buy Me A Coffee" height="41" width="174">
</a>

## Special Thanks

-   Glenn McComb, for his great [article](https://glennmccomb.com/articles/how-to-build-custom-hugo-pagination/) about custom pagination.
-   All contributors, for every PR and Issue reported.