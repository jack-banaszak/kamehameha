# The Kamehameha Hugo Learning Lab
---

GoHugo Homepage: [_link_](https://gohugo.io/)

## Introduction to Hugo  

> _Hugo is a fast and modern static site generator written in Go._

__Pros of Hugo__:
- Extreemly fast and Secure.
- No need for a database.

__What does Hugo Do?__  
Hugo uses a _source directory_ and `templates` to generate a website.  

### Features
__General__:  
- Fast (<1ms per page)
- Uses LiveReload

__Organization__:  
- Customizable URLs + Pretty URLs support
- Configurable __taxonomies__, including _categories_ and _tags_.
- Go _template functions_
- Automatic TOC & Dynamic Menu Creation

__Content__:  

- TOML, YAML, and JSON metadata support in front matter
- Customizable homepage & Multiple content types
- Automatic and user defined content summaries
- __Shortcodes__ to enable rich content inside of Markdown
- functionality {Minutes to Read, WordCount}

__Additional Features__:  
- Integrated Disqus comment support
- Support for Go HTML templates

### The Benefits of Static Site Generators

- Improved performance, security and ease.
- Render content into HTML files. Most are “dynamic site generators.” That means the HTTP server—i.e., the program that sends files to the browser to be viewed—runs the generator to create a new HTML file every time an end user requests a page.
- Over time, dynamic site generators were programmed to cache their HTML files to prevent unnecessary delays in delivering pages to end users. A cached page is a static version of a web page.
- Hugo takes caching a step further and all HTML files are rendered on your computer. You can review the files locally before copying them to the computer hosting the HTTP server. Since the HTML files aren’t generated dynamically, we say that Hugo is a static site generator.
- This has many benefits. The most noticeable is performance. HTTP servers are very good at sending files—so good, in fact, that you can effectively serve the same number of pages with a fraction of the memory and CPU needed for a dynamic site.



## Getting Started
