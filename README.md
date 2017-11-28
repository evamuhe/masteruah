# masteruah
## Commands to install `git` and initialize the repository
  `sudo  apt-get update  
  sudo apt-get install git  

  git config --global user.name "Eva"  
  git config --global user.email "eva@ercavica.com"  
  git config --list  

  mkdir masteruah_local  

  git clone https://github.com/evamuhe/masteruah masteruah_local

  ssh -T git@github.com

  git clone https://github.com/evamuhe/masteruah masteruah_local
  cd masteruah_local/
  git remote set-url origin git@github.com:/evamuhe/masteruah.git

  git add -A
  git status
  git commit -m "testing ssh keys"
  git push`
