# Documentation
You can find our project and API documentation here...

At the moment this is built with [Pandoc](http://pandoc.org/), but we might look into something like [Jekyll Now](https://github.com/barryclark/jekyll-now) if there is some uptake by less tech-savvy people.

Invoke Pandoc e.g. with

```shell
pandoc -f markdown+yaml_metadata_block -o index.html -s -S --template /Users/hagenbruch/PycharmProjects/ubbochum.github.io/rubstrap.html5 index.md
```


A watcher for IntelliJ IDEs can be found in thi [Gist](https://gist.github.com/ahagenbruch/990b03e17052be8e46c4)