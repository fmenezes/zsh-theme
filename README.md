# fmenezes zsh theme

A minimal [Oh My Zsh](https://ohmyz.sh/) theme, based on
[robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).

```
~/code/project [main] ± $
```

- Cyan current directory
- Git branch in brackets, `±` when the working tree is dirty
- `✗` in red with the last exit code when a command fails

## Installation

Clone into your Oh My Zsh custom themes directory:

```sh
git clone https://github.com/fmenezes/zsh-theme ~/.oh-my-zsh/custom/themes/fmenezes
```

Then set the theme in `~/.zshrc`:

```sh
ZSH_THEME="fmenezes/fmenezes"
```

## License

[MIT](LICENSE)
