# Dracula theme for Gollum

This is a custom stylesheet for [Gollum](https://github.com/gollum/gollum) wiki, that uses colours from the [Dracula](https://draculatheme.com) palette to achieve a dark look, that is easy on the eyes.

The stylesheet was hacked together using [Firefox DevTools](https://firefox-source-docs.mozilla.org/devtools-user/index.html), mostly Page Inspector to get IDs and classes whose styles had to be overwritten.


## Usage

1. Download `custom.css` from Codeberg or GitHub.

`curl -sSL https://codeberg.org/totoroot/gollum-dracula-theme/raw/branch/main/custom.css -o custom.css`

`curl -sSL https://raw.githubusercontent.com/totoroot/gollum-dracula-theme/main/custom.css -o custom.css`

1. Copy `custom.css` to the root of your gollum wiki (located at `/wiki` if running the gollum Docker container) and start gollum with option `--css`.


## Contributing

I stopped improving the stylesheet once I had achieved a look that I liked, since I'm using Gollum for my personal wiki/knowledge baseand wanted to have a dark theme that fits the rest of [my desktop](https://codeberg.org/totoroot/dotfiles).

The stylesheet is in no way elegantly designed, but I ain't no frontend guy, so that'll have to do for now.

Feel free to open issues and even more so pull requests in the [Codeberg repo](https://codeberg.org/totoroot/gollum-dracula-theme/) or in the [GitHub repo](https://github.com/totoroot/gollum-dracula-theme/) in case you find any inconsistencies in the theming of the wiki.
