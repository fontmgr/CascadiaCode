## 👋 Welcome to CascadiaCode 🚀  

 Install CascadiaCode fonts  
  
  
### Requires scripts to be installed

```shell
 sudo bash -c "$(curl -q -LSsf https://github.com/fontmgr/installer/raw/main/install.sh)" && sudo fontmgr install installer  
```

OR

### Automatic install/update  

```shell
fontmgr update CascadiaCode
```

OR  

```shell
bash -c "$(curl -q -LSsf "https://github.com/fontmgr/CascadiaCode/raw/main/install.sh")"
```
  
Manual install:  

```shell
git clone "https://github.com/fontmgr/CascadiaCode" "$HOME/.local/share/CasjaysDev/fontmgr/CascadiaCode"
rsync -avhP "$HOME/.local/share/CasjaysDev/fontmgr/CascadiaCode/fonts/." "$HOME/.local/share/fonts/CascadiaCode" --delete
```
  
Manual update:

```shell
git -C "$HOME/.local/share/CasjaysDev/fontmgr/CascadiaCode" pull
rsync -avhP "$HOME/.local/share/CasjaysDev/fontmgr/CascadiaCode/fonts/." "$HOME/.local/share/fonts/CascadiaCode" --delete
```

## Author  

🤖 casjay: [Github](https://github.com/casjay) 🤖  
⛵ fontmgr: [Github](https://github.com/fontmgr) ⛵  
