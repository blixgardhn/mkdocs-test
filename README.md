# mkdocs-test
Tester mkdocs

## For å lage en site i repository

``` docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new . ```

## Live view mens du skriver docs
``` docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material ```

Ref https://squidfunk.github.io/mkdocs-material/creating-your-site/
