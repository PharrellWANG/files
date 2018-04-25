# Static file hosting

## Memo

Remember that Subpath is set in ``_config.yml``.

You should directly update gh-pages branch.

```bash
git checkout gh-pages

bundle update
bundle exec jekyll serve

git add .
git commit -m 'updates'
git push
```

## Example:
1. View PDF version of master thesis in browser

* Shorten URL: <https://git.io/pharrell-master-thesis>

* Real URL: <https://pharrellwang.github.io/files/pdfs/master-thesis.pdf>

2. Download zip package of master thesis

* Shorten URL: <https://git.io/msc-thesis-zip>

* Real URL: <https://pharrellwang.github.io/files/download/master-thesis.pdf.zip>


## List of Files

* Master thesis: https://pharrellwang.com/files/pdfs/master-thesis.pdf
* Progit version2: https://pharrellwang.com/files/pdfs/progit.pdf

## List of Downloadables

* Master thesis: https://pharrellwang.com/master-thesis.pdf.zip
