### [GraphViz Pocket Reference](https://graphs.grevian.org/)

- [GraphViz Formatter](https://github.com/ts-graphviz/prettier-plugin-dot)
- [Dot Language Server](https://github.com/nikeee/dot-language-server)
- [Firefox Filewatcher](https://github.com/coolsoft-ita/filewatcher)
- [Filewatcher](https://github.com/clibs/entr)

```shell
fd \.dot | entr -s 'prettier.sh; for i in *.dot;do dot -Tsvg $i -o ${i%.*}.svg ;done'
```
