# tmux-backupconf

系统环境Arch Linux

配置文件基于[gpakosz](https://github.com/gpakosz/.tmux)

基本上没做什么修改的配置,就是备份一下,以后可以开箱即用,不用再做修改了.

修改了以下内容
- 粘贴模式按键支持vi
- 状态栏置顶
- 鼠标模式开启
- 允许将tmux缓冲区内容复制到系统剪贴板
- 新面板默认为当前路径
- 添加了tmux-continuum和tmux-Resurrect和tpm三个插件
- 取消C+a的按键绑定

插件安装地址:
- [tpm](https://github.com/tmux-plugins/tpm)
- [Tmux Resurrect](https://github.com/tmux-plugins/tmux-resurrect)
- [tmux-continuum](https://github.com/tmux-plugins/tmux-continuum)

安装方式:

git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

git clone https://github.com/tmux-plugins/tmux-resurrect ~/.tmux/plugins/tmux-resurrect

git clone https://github.com/tmux-plugins/tmux-continuum ~/.tmux/plugins/tmux-continuum

复制到系统剪贴板要安装`xsel or xclip`这两个东西

tmux自动恢复要开启一个管理服务(依赖于systemd
具体可查看[rockyourcode](https://www.rockyourcode.com/how-to-start-and-restore-tmux-sessions-automatically-with-tmux-continuum/)


