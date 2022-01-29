# Ubuntu

snap

```
snap list | grep -i intellij
```
```
sudo snap remove intellij-idea-ultimate
```
flatpak
```
flatpak list --app | grep -i intellij
```
```
sudo flatpak uninstall com.jetbrains.IntelliJ-IDEA-Ultimate
```
apt
```
apt list --installed | grep -i intellij
```
```
sudo apt purge intellij-idea-ultimate
```
