# nanoc-bootstrap

*nanoc-bootstrap* is a *nanoc 3* project skeleton using the *Bootstrap* framework and *HAML* templates.

## nanoc, Bootstrap, HAML?

What's this all about?

### nanoc 3

"*Nanoc* is a static-site generator, fit for building anything from a small personal blog to a large corporate website."

See [nanoc.ws](https://nanoc.ws/) for more info - but keep in mind that this project is based on *nanoc 3*, the previous major version of *nanoc*.

### Bootstrap

"*Bootstrap* is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web."

See [getbootstrap.com](http://getbootstrap.com/) for more info.

### HAML

"Beautiful, DRY,  
well-indented, clear markup:  
templating haiku."

See [haml.info](http://haml.info/) for more info.

## Usage

You can just track this repository's `bootstrap` branch:

    [remote "nanoc-bootstrap"]
        url = https://github.com/th-h/nanoc-bootstrap.git
        fetch = +refs/heads/*:refs/remotes/nanoc-bootstrap/*
    [branch "bootstrap"]
        remote = nanoc-bootstrap
        merge = refs/heads/bootstrap

See [bootstrap.md](_doc/bootstrap.md) for more information.
