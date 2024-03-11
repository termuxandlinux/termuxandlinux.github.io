# This is a own Pakage Repo for Arch and Debian

Arch is Available/ Debian is comming soon

## Arch

run as root

```bash
nano /etc/pacman.conf
```

On the Last Line set

```
[termuxandlinux-repo]
Server = https://termuxandlinux.github.io/arch/
```

Then Run

```
sudo pacman -Sy
```

After this

```
sudo pacman -S termuxandlinux-repo/pakage
```
