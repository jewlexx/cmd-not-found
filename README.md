# cmd-not-found
A zsh hook for when your command cannot be found

> NOTE: Only works on Arch for now

## Installtion: 

If you have an AUR helper (eg. `yay`):

```shell
yay -S cmd-not-found
```

Otherwise:

```shell
git clone https://aur.archlinux.org/cmd-not-found.git
cd cmd-not-found
makepkg -si
```

Then add the following line to your `.zshrc`:

```shell
source /usr/share/zsh/functions/cmd-not-found.zsh
```

**Made with ❤️ by Juliette Cordor**
