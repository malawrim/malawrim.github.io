### Check out website at <a class="nav-link" href="https://malawrim.github.io/">malawrim.github.io</a>

Template for personal website from Jekyll Mediumish Theme

```
malawrim.github.io
│   404.html - use when page isn't found
│   Gemfile - manage Jekyll version and plugins
│   index.html - landing page - calls featured and general posts - pulls in format from \_layouts/default.html
│   _config.yml - includes title, site name, authors, plugins
│
├───assets
│   ├───css
│   │       main.scss
│   │       screen.css
│   │
│   ├───fonts
│   │       casper-icons fonts
│   │
│   ├───images
│   │       all images *.jpg
│   └───js
│           ie10-viewport-bug-workaround.js
│           jquery.min.js
│           lazyload.js
│           lunr.js
│           lunrsearchengine.js - generates search bar
│           mediumish.js
│
├───site
│       _config.yml
│
├───_includes
│       adsense-under-header.html
│       disqus.html - if enabling comments on posts
│       featuredbox.html - set up box for featured post (labeled "current projects" in this implementation)
│       pagination.html
│       postbox.html - set up box for featured post (labeled "past work" in this implementation)
│       search-lunr.html - set up search bar
│       share.html - for connecitng to social is using
│       toc.html - table of contents
│
├───_layouts
│       archive.html - use if archiving any pages
│       categories.html - sets up page categories if using
│       default.html - default page layout - called in index.html
│       page.html - calls default - template for non-posts
│       post.html - calls default - template for any posts
│       tags.html - sets up tags if using
│
├───_posts
│       all posts *.md
│
└───_sass
        _stars.scss
        _starsnonscss.scss
        _syntax.scss
```
