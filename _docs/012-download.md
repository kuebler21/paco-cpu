---
title: "Download"
permalink: /docs/download/
excerpt: "How and where from can the PACO toolchain be downloaded."
modified: 2016-08-08T16:25:30-04:00
---

## Download
To prevent you from cloning all subdirectories of the project by yourself, you can download the content from the master directory: (TODO: add link)
Be aware that all data will need about 18GB. 

## Repository structure

Here you can take a look into the structure to have a clue how the repositories are located correct. 

# TODO: make a structure like the examle below with all our repositories



#### The navigation below is not removed as a hint for documentation of the project structure

```bash
minimal-mistakes
├── _data                      # data files for customizing the theme
|  ├── navigations.yml         # main navigation links
|  └── ui-text.yml             # text used throughout the theme's UI
├── _includes
|  ├── analytics-providers     # snippets for analytics (Google and custom)
|  ├── comments-providers      # snippets for comments (Disqus, Facebook, Google+, and custom)
|  ├── footer                  # custom snippets to add to site footer
|  ├── head                    # custom snippets to add to site head
|  ├── base_path               # site.url + site.baseurl shortcut
|  ├── feature_row             # feature row helper
|  ├── gallery                 # image gallery helper
|  ├── group-by-array          # group by array helper for archives
|  ├── nav_list                # navigation list helper
|  ├── toc                     # table of contents helper
|  └── ...
├── _layouts
|  ├── archive-taxonomy.html   # tag/category archive for Jekyll Archives plugin
|  ├── archive.html            # archive listing documents in an array
|  ├── compress.html           # compresses HTML in pure Liquid
|  ├── default.html            # base for all other layouts
|  ├── single.html             # single document (post/page/etc)
|  └── splash.html             # splash page
├── _sass                      # SCSS partials
├── assets
|  ├── css
|  |  └── main.scss            # main stylesheet, loads SCSS partials from _sass
|  ├── fonts
|  |  └── fontawesome-webfont  # Font Awesome webfonts
|  ├── js
|  |  ├── plugins              # jQuery plugins
|  |  ├── vendor               # vendor scripts
|  |  ├── _main.js             # plugin settings and other scripts to load after jQuery
|  |  └── main.min.js          # optimized and concatenated script file loaded before </body>
├── images                     # image assets for posts/pages/collections/etc.
├── _config.yml                # site configuration
├── Gemfile                    # gem file dependencies
├── Gemfile.lock               # gem file dependencies
├── index.html                 # paginated home page showing recent posts
└── package.json               # NPM build scripts
```
