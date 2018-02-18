比如安装pip或者pip3时遇到这种情况：
    $ locale.Error: unsupported locale setting
    
那么可以这样解决：
    vi ~/.bashrc
在最后面输入：
    export LC_ALL=C
再次安装pip时，locale错误即可以解决

详细原因在这里： https://unix.stackexchange.com/questions/87745/what-does-lc-all-c-do