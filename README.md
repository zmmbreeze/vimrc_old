此配置未在windows下测试过，只支持linux和mac。

安装步骤：

1. 安装git，注册github
2. 先设置sshkey：http://help.github.com/set-up-git-redirect/
3. git clone https://github.com/zmmbreeze/vimrc.git
4. 拷贝下载下来的文件夹中的代码到~/目录下
5. git pull
6. git submodule update --init --recursive
7. 安装文件夹里面的字体
8. 编译[YouCompleteMe](https://github.com/Valloric/YouCompleteMe)
9. 安装[tern_for_vim](https://github.com/marijnh/tern_for_vim#installation)，实现javascript自动补全功能
