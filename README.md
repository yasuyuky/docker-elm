# Docker Image for minimal elm environment

# Usage

Change directory to your project root.

Then you enter into docker image.

```
docker run -it --rm -v ${PWD}:/source yasuyuky/elm
```

and elm commands works.

# Alias

to use elm commands like local commands,
the following setting may be useful.

```
alias elm="docker run -it --rm -v ${PWD}:/source yasuyuky/elm elm"
```

# License

MIT
