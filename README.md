# jebeniposten.hr

https://jebeniposten.hr
On dev branch create content/artical-foo.md 
Then:

pelican content -o output -s pelicanconf.py
ghp-import output -b gh-pages
git push https://github.com/jebeniposten/jebeniposten.github.io gh-pages:master