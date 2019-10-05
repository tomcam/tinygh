# tinygh is the minimal GitHub Pages/Jekyll test, with some VuePress observations

See this on [GitHub Pages](https://tomcam.github.io/tinygh/)

This is a minimal Jekyll-style installation, which means it works on GitHub Pages.
There's also some compatibility with VuePress. It consists of:

* Base `/docs` directory
* A README.md that links to another page
* An orphan page named todo.md that no other page links to
* A `_posts` directory with three posts in it. Some of the posts are malformed to see 
how well they're rendered:
  * The post for January 1 2019 is properly formed. The post for February 1 2019 is missing a `title` in the
front matter. And the post for March 1 2019 has no front matter at all.

## Things it lacks
* Any kind of custom  HTML or CSS
* Any kind of Jekyll templates
* Handling of the `_posts` directory in blog file (because no Jekyll templates)
* A `_config.yml` file (helps observe behavior when themes are changed)

## VuePress notes

* In VuePress, the `_posts` directory is invisible because it lacks a README.md
* The double braces below cause serious rendering problems with current versions of VuePress

Link to another [page](page.md), and link to the [posts](_posts.md) directory.

Jekyll reports the theme is: {{ site.theme }}
