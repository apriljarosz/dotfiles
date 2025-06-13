Dotfile Setup, Managed using Chezmoi

Install:
```shell
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --ssh --apply apriljarosz
```

Remove: 
```shell
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --one-shot apriljarosz
```
