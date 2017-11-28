# masteruah
## Commands to install `git` and initialize the repository
### Install the package in Ubuntu:
```
sudo  apt-get update  
sudo apt-get install git  
```

### Configure `git`
```
git config --global user.name "Eva"  
git config --global user.email "eva@ercavica"  
git config --list  
```

### Create ssh keys and perform initial sync with GitHub
```
mkdir masteruah_local  
ssh -T git@github.com
git clone https://github.com/evamuhe/masteruah masteruah_local
cd masteruah_local/
git remote set-url origin git@github.com:/evamuhe/masteruah.git
```

### Modify some files and push the changes
```
git add -A
git status
git commit -m "testing ssh keys"
git push
```
