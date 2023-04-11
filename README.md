### malawrim.github.io
Template for personal website from Jekyll Mediumish Theme

Explaination of file system:

malawrim.github.io
  ### 
    config.yml - includes title, site name, authors, plugins
    index.html - landing page - calls featured and general posts - pulls in format from \_layouts/default.html
    Gemfile - manage Jekyll version and plugins
  ### \_includes
    postbox.html
    featuredbox.html
    pagniation.html
    search-lunr.html
    share.html
    toc.html
  ### \_layouts
    default.html
    page.html
    post.html
  ### \_posts
    2018-01-12-second_example.html
    2023-04-11-example.html
  ### \_sass
    \_stars.scss
    \_starsnonscss.scss
    \_syntax.scss
  ### assets
    #### css
    #### fonts
    #### images
    #### js
  ### site
    #### \_config.yml
```bash
│   .gitignore
│   404.html
│   changelog.md
│   docker-compose.yml
│   favicon.ico
│   feed.xml
│   Gemfile
│   Gemfile.lock
│   index.html
│   LICENSE.txt
│   README.md
│   _config.yml
│
├───assets
│   ├───css
│   │       main.scss
│   │       screen.css
│   │
│   ├───fonts
│   │       casper-icons.eot
│   │       casper-icons.svg
│   │       casper-icons.ttf
│   │       casper-icons.woff
│   │
│   ├───images
│   │       1.jpg
│   │       10.jpg
│   │       11.jpg
│   │       12.jpg
│   │       13.jpg
│   │       14.jpg
│   │       15.jpg
│   │       16.jpg
│   │       17.jpg
│   │       2.jpg
│   │       3.jpg
│   │       4.jpg
│   │       5.jpg
│   │       6.jpg
│   │       7.jpg
│   │       8.jpg
│   │       9.jpg
│   │       avatar.png
│   │       jumbotron.jpg
│   │
│   └───js
│           ie10-viewport-bug-workaround.js
│           jquery.min.js
│           lazyload.js
│           lunr.js
│           lunrsearchengine.js
│           mediumish.js
│
├───site
│       _config.yml
│
├───_includes
│       adsense-under-header.html
│       disqus.html
│       featuredbox.html
│       pagination.html
│       postbox.html
│       search-lunr.html
│       share.html
│       star_rating.html
│       star_rating_postbox.html
│       toc.html
│
├───_layouts
│       archive.html
│       categories.html
│       default.html
│       page.html
│       post.html
│       tags.html
│
├───_posts
│       2018-01-12-second_example.md
│       2023-04-11-example.md
│
└───_sass
        _stars.scss
        _starsnonscss.scss
        _syntax.scss
```
