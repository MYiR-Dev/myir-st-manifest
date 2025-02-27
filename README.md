# myd-ld25x mainifest
#note: The Python version > 3.0
cmd:

1: export REPO_URL='https://mirrors.tuna.tsinghua.edu.cn/git/git-repo/'

2: repo init -u https://github.com/MYiR-Dev/myir-st-manifest.git --no-clone-bundle --depth=1 -m myir-stm32mp2-6.6.48-1.0.0.xml -b myd-ld25x-v24.12.05-scarthgap

3: repo sync
