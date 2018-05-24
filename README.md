1.git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

2.bshui# git clone https://github.com/Kylinshui/vim.git

3.bshui# cp vim/.vimrc ~/

4.在vim中输入PluginInstall自动安装插件

5.编译YouCompleteMe
vim# apt-get install python-dev python3-dev python-pip cmake
vim# pip install requests
vim# cd ~/.vim/bundle/YouCompleteMe/
YouCompleteMe# ./install.py --clang-completer

6.配置
YouCompleteMe# cp third_party/ycmd/examples/.ycm_extra_conf.py ~/.vim/

7.测试


8.vim# apt-get install ctags cscope

9.使用make命令生成ctags和cscope

linux-4.16.7# export ARCH=arm
linux-4.16.7# export CROSS_COMPILE=arm-linux-gnueabi-
linux-4.16.7# make vexpress_defconfig
linux-4.16.7# make tags cscope TAGS //生成tags,cscope,TAGS索引文件

