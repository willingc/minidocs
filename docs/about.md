# about minidocs

This module generates a documentation site from two simple components: 

1. A collection of markdown documents
2. A hierarchical object specifying your table of contents

This module is intentionally simpler and more opinionated than something like [Jekyll](https://jekyllrb.com/) or [Sphinx](http://www.sphinx-doc.org/en/stable/). Depending on what you're looking for, that might be good, because it's easier to reason about, or bad, because it's less flexible! It'll probably be most useful if your documentation already consists entirely of markdown files, and it composes well with any tools that generate markdown, for example [`ecosystem-docs`](https://github.com/hughsk/ecosystem-docs), which pulls README files from a collection of GitHub repositories.

Sites can be built using a command-line tool, or using the library as a module with browserify. There are options for specifying a project logo, custom css, and other basic formatting.Support for themes coming soon! PRs welcome!