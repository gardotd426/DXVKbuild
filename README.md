# DXVKbuild
Prebuilt DXVK 1.6 with async patch
For use with wine, just clone the repo, and copy the 1.6-async directory into `~/.local/share/lutris/runtime/dxvk`...
```
gc https://github.com/gardotd426/DXVKbuild.git
cd DXVKbuild
cp -r 1.6-async ~/.local/share/lutris/runtime/dxvk/
```
then in whichever game you want to run with DXVK with async in Lutris, open up the configuration menu, and under "DXVK Version" type `1.6-async`, and add `DXVK_ASYNC=1` to launch options. 
