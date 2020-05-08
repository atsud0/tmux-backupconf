# tmux-backupconf

配置文件基于[gpakosz](https://github.com/gpakosz/.tmux)

此配置文件中,暂时不知道为什么tmux-continuum不会生效,可不安装

基本上没做什么修改的配置,就是备份一下,以后可以开箱即用,不用再做修改了.

修改了以下内容
- 粘贴模式为vi模式
- 状态栏置顶
- 鼠标模式开启
- 允许将tmux缓冲区内容复制到系统剪贴板
- 新面板默认为当前路径
- 添加了tmux-continuum和tmux-Resurrect和tpm三个插件

插件安装地址
- [tpm](https://github.com/tmux-plugins/tpm)
- [Tmux Resurrect](https://github.com/tmux-plugins/tmux-resurrect)
- [tmux-continuum](https://github.com/tmux-plugins/tmux-continuum)

取消C+A的按键绑定要在.tmux.conf中修改
