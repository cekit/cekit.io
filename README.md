
# CEKit Website

The CEKit [website](https://cekit.io) uses [Hugo](https://github.com/gohugoio/hugo) to generate its content.

## Local Development

* Check out this repository
* Check out the git submodules via

```
git submodule init
git submodule update
```

* Ensure both Hugo and Asciidocter are installed.
    * On Fedora they may be installed from RPMs (`hugo` and `rubygem-asciidoctor` respectively).

* Then the hugo server may be run for local development e.g.

```
hugo server --buildDrafts --buildFuture --verbose
```

Note that the `--buildFuture` flag allows blog posts that are scheduled for future to be shown.
