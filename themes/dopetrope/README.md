# Dopetrope

Dopetrope theme ported from [HTML5 UP](https://html5up.net/) for use with the [Hugo static site generator](https://gohugo.io/).

Theme includes ability for:

 - Portfolio items
 - Blog posts

![](images/device-screenshots.png)

## Demo

https://hugo-theme-dopetrope.netlify.com/

## Setup

### Configuration

See the demo's configuration as an example:

https://github.com/curttimson/hugo-theme-dopetrope/blob/master/exampleSite/config-prod.toml

### Front Matter

 - `description`
 - `date`
 - `thumbnail`
 - `image`
 - `title`
 - `slug`
 - `author`
 - `draft`
 - `hidesidebar` - Set to false to hide the sidebar on specific pages

### Blog Comments

Blog comments are supported by Disqus. Once set up comments will be displayed on the blog posts as well as a count on the homepage.

If not set up already, create a Disqus account and enter the account name in the `config.toml` file:


### Cover Image

The cover image URL is hard-coded, therefore to replace this add an image to the following location in your Hugo application:

```
/static/images/pic01.jpg
```

## Development

### Example Site Deployment

```
$ hugo --config config-prod.toml
```

## Original Theme Credits

 - [Dopetrope by HTML5 UP](https://html5up.net/dopetrope)

## License

This hugo theme is licensed under the [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/).

Read More - [LICENSE](LICENSE)
