# TL;DR

```sh
sudo pacman -S pandoc entr python

# rerun build script whenever a `index.md` or `template.html` file is updated:
find . \( -name index.md -o -name template.html \) | entr python build.py

# host static website locally at port 8000:
python -m http.server --bind localhost
```
