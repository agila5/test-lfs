  408  git clone https://github.com/agila5/test-lfs.git
  409  git status
  410  git add simulate-data.R 
  411  git commit -m "setup"
  412  git lfs install
  413  git lfs track '*.csv'
  414  git add .gitattributes 
  415  git add data/test.csv 
  416  git status
  417  git commit -m "test lfs"
  418  git status
  419  git lfs ls-files
  420  git push
  423  history
  425  history > README.md
