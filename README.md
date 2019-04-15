# patch

## _tar
patch to disable version output when press tab key after tar command at zsh

### darwin
```
tar_patch=$PWD/_tar.patch
cd /usr/local/share/zsh/functions/
# e.g. cd /usr/local/Cellar/zsh/5.7.1/share/zsh/functions/
cat $tar_patch | patch -p1
```


### ubuntu
```
tar_patch=$PWD/_tar.patch
# e.g.
cd ~/.linuxbrew/Cellar/zsh/5.7.1/share/zsh/functions/
cat $tar_patch | patch -p1
```
