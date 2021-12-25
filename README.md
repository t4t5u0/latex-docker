# Docker image for LaTeX

## Usage

カレントディレクトリにビルドしたいtexソースがあるとする．

```bash
$ docker run -u $(id -u):$(id -g) --rm -v $PWD:/workdir t4t5u0/lualatex:1 latexmk main.tex
```

これでカレントディレクトリに`main.pdf`ができる．

## Version
<!-- 
| Image tag | Ubuntu | TeXLive |
| --------- | ------ | ------- |
| 1.0.0     | 19.10  | 2019    |
| 1.1.0     | 19.10  | 2019    |
| 1.2.0     | 19.10  | 2019    |
| 2.0.0     | 20.04  | 2020    |
 -->
## Author

t4t5u0

## License

MIT

