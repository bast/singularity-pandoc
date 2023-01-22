# Singularity recipe for [Pandoc](https://pandoc.org/)

How to fetch and use the image:
```
$ singularity pull https://github.com/bast/singularity-pandoc/releases/download/0.3.0/pandoc.sif
$ ./pandoc.sif --from=markdown --to=rst --output=README.rst README.md
```

I have used this wonderful guide as starting point and inspiration:
https://github.com/singularityhub/singularity-deploy
