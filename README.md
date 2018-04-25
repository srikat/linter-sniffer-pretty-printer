# Sniffer, Linter, Pretty Printer

A collection of configurations for the PHPCS code sniffer, the Eslint JavaScript linter and the Stylelint CSS linter for your WordPress projects.

## Disclaimer

I don't guarantee that using the configurations in this repository ensure 100% adherence to the official WordPress coding standards.

As a matter of fact, the following warning was given on the WP Australia Slack group:

> My recommendation is to _not_ use it, you won’t be adhering to WordPress’s coding standards if you use that repo
> A whole bunch of things, there are _official_ packages with official coding standards, those are the packages that should be used.

Please use at your own discretion or write your own package.json and configs (maybe without Prettier).

## Origin of configs/packages (installed from npm or packagist):

eslint-config-wordpress: https://github.com/WordPress-Coding-Standards/eslint-config-wordpress

Installation instructions from the readme:

> Add this to your .eslintrc.json file: "extends": "wordpress"

stylelint-config-wordpress: https://github.com/WordPress-Coding-Standards/stylelint-config-wordpress

Installation instructions from the readme:

> If you've installed stylelint-config-wordpress locally within your project, just set your stylelint config to:
> {
> "extends": "stylelint-config-wordpress"
> }

stylelint-order: https://sridharkatakam.com/format-css-per-wordpress-coding-standards-using-csscomb-sublime-text

WPCS: https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards

The phpcs.xml.dist is slightly opinionated and based on https://github.com/copyblogger/genesis-sample/blob/develop/phpcs.xml.dist

## Why Prettier?

Because it makes life easier. But it might cause deviations from pure WordPress coding standards.

Sridhar Katakam has written a tutorial on how to setup Visual Studio Code with Prettier and the configs in this repo. https://sridharkatakam.com/linting-and-formatting-in-visual-studio-code-for-wordpress/
