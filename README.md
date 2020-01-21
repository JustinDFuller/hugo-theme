# hugo theme

This is the theme for my [hugo blog](https://github.com/JustinDFuller/blog). See [justindfuller.com](https://justindfuller.com) for an example of this theme in use.

![Screenshot](https://image.thum.io/get/maxAge/12/width/700/https://justindfuller.com "Screenshot")

## Usage
Clone the repository to your site's `themes` directory. Refer to [`exampleSite/config.toml`](https://github.com/alanorth/hugo-theme-bootstrap4-blog/blob/master/exampleSite/config.toml) for recommended configuration values.

## Content Suggestions
A few suggestions to help you get a good looking site quickly:

- Keep blog posts in the `content/posts` directory, for example: `content/posts/my-first-post.md`
- Keep static pages in the `content` directory, for example: `content/about.md`
- Keep media like images in the `static` directory, for example: `static/2016/10/screenshot.png`
- If you want an image to be shown when you share a post on social media, specify at least one image in the post's front matter, for example: `images: ["/2016/10/screenshot.png"]`
- Use the `<!--more-->` tag in posts to control how much of a post is shown on summary pages
- Disable comments on a post by setting `comments = false` in its frontmatter
- Disable social sharing icons site wide (or on individual pages/posts) by setting `sharingicons = false`
- If your content is stored in git, add `enableGitInfo = true` to your site config and Hugo will use git history to set a more accurate modification date in page metadata

See the source code and structure of [picturingjordan.com](https://github.com/alanorth/picturingjordan.com) to get more ideas.

## Building (For Developers)
This theme uses the [Bootstrap](https://getbootstrap.com/) framework. A static version of this is already included, but if you want to bump the version, tweak the style, etc, you'll need to rebuild the assets. Make sure you have NodeJS >= v6 installed, and then run the following from inside the theme's directory:

```console
$ npm install
$ npm run build
```

## License
This repository contains SASS and HTML code from the [Bootstrap](https://getbootstrap.com) project, which is licensed under the [MIT license](https://tldrlegal.com/license/mit-license) and [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/), and [Font Awesome](https://fontawesome.com/), which uses [various licenses](https://fontawesome.com/license/).
