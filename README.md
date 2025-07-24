# Compatpak repository
Repository of compatibility Flatpaks.
# Adding
```console
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
```
```console
flatpak remote-add --if-not-exists compatpak https://compatpak.github.io/repo/compatpak.flatpakrepo
```
# Removing
```console
flatpak remote-delete compatpak
```
# Update Metainfo
```console
flatpak build-update-repo --gpg-sign=GPGKey repo
```