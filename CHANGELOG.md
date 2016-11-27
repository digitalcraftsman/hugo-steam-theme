# Changelog

### 27th November 2016

- `favicon` allows you to link a custom favicon by adding a path relative to the `static` folder
- with `customCSS` and `customJS` you can link your own stylesheets and scripts. The files have to be link relative to `static` as well.

### 26th November 2016

Some of the new features of Hugo v0.17 were now introduced in this theme. Since some changes are not backwards compatible you have to update to Hugo v0.17 or newer versions.

- Steam now uses the Google Analytics template that is shipped with Hugo. Just move the `googleAnaltics` variable outside the `params` block. Have a look at the [example config file](https://github.com/digitalcraftsman/hugo-steam-theme/blob/master/exampleSite/config.toml).
- The support for Google Plus comments in now deprecated.
- Formerly, it was only possible to show pages of `type` post on the homepage. Now, all types of pages are shown. You can hide single pages by adding `hide = true` to the (TOML) frontmatter.
- External dependencies like Highlight.js have been updated to the latest version.
