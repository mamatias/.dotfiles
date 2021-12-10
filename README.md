# .dotfile

Humilde recopilación de archivos de configuración (.dotfiles)

## Uso

  1) Primero hay que instalar stow.
```bash
# debian
sudo apt install stow

# manjaro
sudo pacman -S stow
```
Stow permite mantener en sincronía los dotfiles del directorio `~/.dotfiles` con el directorio `~`.

2) Se debe tener el directorio `~/.dotfiles` y para ello se clona el repositorio.

```bash
git clone git@github.com:mamatias/.dotfiles.git
```

3) Con el directorio ya existente se debe ingresar a el y luego aplicar la sincronización con `stow .`
```bash
cd ~/.dotfiles
stow .
```