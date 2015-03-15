# Precede

> A style-less theme for Ghost, intended as a starting point.

Precede is a style-less theme for [Ghost](https://github.com/TryGhost/Ghost), it is intended to be used as a starting point for creating new themes.

There are 2 versions, one with an empty `styles.css` file, and another with Sass already setup. That includes `grunt-sass` and a set of Grunt tasks to make release zips so you can more easily distribute your theme without including `node_modules` and any other files never used in a Ghost theme.

## Getting Started

Forking this repository if you want to make a new theme doesn't make sense, as every change will be bespoke. Instead, download the a release zip and start from there.

- [Download a release zip](https://github.com/PaulAdamDavis/Precede/releases)
- Unzip in your local Ghost project, under `ghost/content/themes/Precede`
- Rename the theme folder `mv Precede TheNewName`
- Open `package.json` and change the name there too.
- Go mad with your new changes!

## Features

This starter theme will have every feature Ghost has, in its rawest form. The goal here is to give you all the theme tags and files ready to use, so you only need to add things that make your theme yours.

Parts of the theme such as pagination and navigation usually use a built-in partial, but can also use a custom partial. In these cases, a custom partial is already used so make it easier for you to customise.

- Home page
- Pagination
- Navigation
- Tag pages
- Author pages
- Cover images
- Posts
- Pages

## License

Precede is released under the MIT license, so you can do whatever you want, with no restrictions.