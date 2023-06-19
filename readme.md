# Pure

> Pretty one-line ZSH prompt based on [@sindresorhus](https://github.)'s [Pure](https://github.com/sindresorhus/pure)

## Install

1. Clone this repo somewhere. Here we'll use `$HOME/.zsh/pure`.

```sh
mkdir -p "$HOME/.zsh"
git clone https://github.com/sindresorhus/pure.git "$HOME/.zsh/pure"
```

2. Add the path of the cloned repo to `$fpath` in `$HOME/.zshrc`.

```sh
# .zshrc
fpath+=($HOME/.zsh/pure)
```

## Getting started

Initialize the prompt system (if not so already) and choose `pure`:

```sh
# .zshrc
autoload -U promptinit; promptinit
prompt pure
```

## Options

See [pure's options](https://github.com/sindresorhus/pure#options).
