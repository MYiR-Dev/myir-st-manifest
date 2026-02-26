# myd-yf13x mainifest
#note: The Python version > 3.0
cmd:
1.  chmod a+x ~/bin/repo

2.  export PATH=~/bin:${PATH}

3:  export REPO_URL='https://mirrors.ustc.edu.cn/aosp/git-repo.git/'

4: repo init -u https://github.com/MYiR-Dev/myir-st-manifest.git --no-clone-bundle --depth=1 -m myd-yf13x-6.6.78-1.0.0.xml -b myd-yf13x-v25.06.11-scarthgap

5: repo sync
