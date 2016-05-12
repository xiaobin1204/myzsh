# myzsh

#安装zsh
<ol>
    <li>查看本机已安装的shell</li>
    <span>cat /etc/shells</span>
    <li>安装zsh</li>
    <span>sudo yum install zsh</span><br>
    <span>sudo apt-get install zsh</span><br>
    <span>安装完成后 chsh -s /bin/zsh 输入相应用户密码</span>
    <li>安装git</li>
    <span>sudo yum install git</span><br>
    <span>sudo apt-get install git</span>
    <li>安装oh my zsh</li>
    <span>自动安装: wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh</span><br>
    <span>手动安装： git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh </span><br>
    <span>cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc</span><br>
    <span>安装完成后重启终端</span>
    <li>安装autojump</li>
    <span>mac： brew install autojump</span><br>
    <span>linux wget https://github.com/downloads/joelthelion/autojump/autojump_v21.1.2.tar.gz</span><br>
    <span>进入目录 ./install.sh</span><br>
    <span>[[ -s ~/.autojump/etc/profile.d/autojump.sh ]] && . ~/.autojump/etc/profile.d/autojump.sh </span><br>
    <span>把提示的这一句添加到.zshrc里</span>
</ol>