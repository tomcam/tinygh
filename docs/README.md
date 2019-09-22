# tinygh is the smallest GitHub Pages test

A miniature Jekyll-style installation with
* Base `/docs` directory
* A README.md that links to another page
* An orphan page named todo.md that no other page links to
* A `_posts` directory with three posts in it. However:
* The post for January 1 2019 is properly formed. The post for February 1 2019 is missing a `title` in the
front matter. And the post for March 1 2019 has no front matter at all.

Things it lacks
* Any kind of custom  HTML or CSS
* A `_config.yml` file (helps observe behavior when themes are changed)

Link to another [page](page.md)
