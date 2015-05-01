# Using Twitter Bootstrap

This site is build from (Twitter) Bootstrap **v3.3.4** (see
[http://getbootstrap.com/](http://getbootstrap.com/)) by *nanoc*.

## Installing Bootstrap

*CSS* is compiled from *LESS*, fonts and *Javascript* are taken
"as is".

| Directory ... |   ... is copied to ...     |
|:-------------:|:--------------------------:|
| `dist/js/`    | `content/bootstrap/js/`    |
| `fonts/`      | `content/res/fonts/`       |
| `less/`       | `content/bootstrap/less/`  |

Fonts need to be renamed; `bootstrap.min.js` needs to be renamed to
`bootstrap-min.js`, too.

## Compilation

|       Files in ...         |   ... are compiled to ...    |
|:--------------------------:|:----------------------------:|
| `content/res/fonts/`       |        `res/fonts/*`         |
| `content/bootstrap/js/`    |          `res/js/*`          |
| `content/bootstrap/less/`  |   `res/css/bootstrap.css`    |

# Updating Bootstrap

Updates from the *bootstrap* branch can just be merged.

    $ git checkout bootstrap
    # update bootstrap
    $ git checkout master; git merge bootstrap
