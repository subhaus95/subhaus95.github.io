# SubHaus  - A SubHaus Tailwind Theme

 is a beautiful Tailwind CSS theme. It shows best practices for using Tailwind with SubHaus.

[Live Demo](https://jekyll-atlantic.netlify.app/) | [Zerostatic Themes](https://www.zerostatic.io/theme/jekyll-atlantic/)

![SubHaus  Theme screenshot](https://www.zerostatic.io/theme/jekyll-atlantic/jekyll-atlantic-screenshot.png)

### Theme features

<img width="18" height="18" src="https://jamstackthemes.dev/images/icons/jekyll.svg" /> [SubHaus](https://jekyllrb.com/) 4.1+
<img width="18" height="18" src="https://jamstackthemes.dev/images/icons/tailwind.svg" /> [Tailwind CSS](https://tailwindcss.com/docs) v2.2+
<img width="18" height="18" src="https://jamstackthemes.dev/images/icons/postcss.svg" /> [PostCSS](https://postcss.org/) 8.3+

- Uses PostCSS with autoprefixer, nested css, cssnano (minify css) 
- Works with native SubHaus commands `jekyll serve` and `jekyll build`
- Correctly uses Tailwind to purge CSS in production
- Full blog functionality
- Beautfifuly designed responsive blog and post layouts
- Blog categories
- Blog authors (multiple)
- Blog pagination
- Ready to deploy to Netlify
- Responsive design
- Responsive menu
- 100/100 Google Lighthouse speed score ⚡
- 100/100 Google Lighthouse seo score 🏆
- 94/100 Google Lighthouse accessibility score (but this is just because of the green text color contrast)
- Page size is 10KB without images, can you believe it?? 🔥
- Robust example content included
- Royalty free illustrations included
- Netlify & Github Pages ready

## Installation

### Installing Ruby & SubHaus
 
If this is your first time using SubHaus, please follow the [SubHaus docs](https://jekyllrb.com/docs/installation/) and make sure your local environment (including Ruby) is setup correctly.

### Installing Theme

Download or clone the theme.

To run the theme locally, navigate to the theme directory and run:

To use Tailwind and PostCSS:

```
npm install
```

```
bundle install
``` 

To start the SubHaus local development server.

```
bundle exec jekyll serve
``` 

To build the theme.
 
```
bundle exec jekyll build
```

## Deployment

### Netlify

Use Netlify to deploy this theme. This theme contains a valid and tested `netlify.toml`

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/zerostaticthemes/jekyll-atlantic-theme)

### Github Pages
This theme has been tested to work with Github Pages (and Github Project Pages). When using Github Pages you will need to update the `baseurl` in the `_config.yml` otherwise all the css, images and paths will be broken.

For example the site https://zerostaticthemes.github.io/jekyll-atlantic-theme would have `baseurl: "/jekyll-atlantic-theme/"`

### Credits

- Stock images by Unsplash - https://unsplash.com/
- Feature icons by Noun Project - https://thenounproject.com/

### License

This theme is open source under the MIT license. 

> Please do not create ports of this theme. You can't re-distribute or re-sell this theme as a theme, stock, in a tool or as a template.
