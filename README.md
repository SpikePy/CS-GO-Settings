# CSGO
Just a place to archive my autoexec.cfg of CS:GO

## Setup
```
cd /mnt/c/Games/Steam/steamapps/common/Counter-Strike\ Global\ Offensive/csgo/cfg
repo='git@github.com:SpikePy/CSGO.git'

clear
rm -rf .git autoexec.cfg README.md
git init
git remote add origin $repo
git fetch
git checkout -t origin/master -f
cd -
```
