-command_not_found_handle() {
	/data/data/com.termux/files/usr/libexec/termux/command-not-found "$1"
}
clear
cmatrix -C red -s
red='\e[1;31m'
green='\e[1;32m'
blue='\e[1;34m'
purple='\e[1;35m'
cyan='\e[1;36m'
white='\e[1;37m'
yellow='\e[1;33m'
echo -e "\e[97m                      ______
                   .-        -.
                  /            \ \033[1m \e[31mBY\033[1m \e[34m.\033[1m \e[31m•@QNQQ8•
     \e[94m* \e[97m                   \e[90m* \e[97m
                 |,  .-.  .-.  ,|        \e[32m* \e[97m
                 | )(_ /  \ _)( |
                 |/     /\     \|    \e[34m* \e[97m
       (@_       <__    ^^    __>         \e[95m* \e[97m
 _      ) \_______\__|IIIIII|__/_________\e[31m_______ \e[97m
(_)\e[31m@8@8\e[97m{}<________\e[31m_____\e[97m__________\e[31m________________> \e[97m
        )_/         \ IIIIII /              \e[31m::::: \e[97m
       (@            --------                  \e[31m:: \e[97m
        "
                                       #
PS1='\[\033[1;32m\]┌────\033[1;31m[@5T_O8]\033[1;32m────────────────────\033[1;37m[\T]\e[1;32m─┐\n\e[1;31m#\e[1;34m[\W]\e[1;31m\n└>•ASTRH•# '





alias x='exit'
alias c='clear'
alias p='python'
alias n='nano'
alias b='nano .bashrc'
alias pp='python2'
alias m='chmod +x'
alias g='git clone'
alias r='rm -rif'
alias sd='cd /sdcard'
alias l='ls'
alias la='ls -a'
