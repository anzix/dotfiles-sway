# Dotfiles-Sway
Установка через GNU Stow
```
sudo pacman -S stow
```
```bash
git clone https://gitlab.com/anz1x/dotfiles-sway && cd dotfiles-sway/base
```
```bash
# Вытащить всё
stow -vt ~ */
```
```bash
# Вытянуть отдельную папку
stow -vt ~ sway
```

* (n) - это означает что действия будут эмитироватся
* (v) - это означает что действия будут подробными
* (t) - целевая директория
* (/) - это означает что файлы по типу README.md и обоев будут игнорироваться
* (*) - это означает что stow будет вытягивать всё из папки dotfiles в целевую директорию
* (~) - это HOME диретория
