alias k='kubectl'
export ZSH=$HOME/.oh-my-zsh
export PATH=/usr/local/bin:$PATH
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk-11.0.1+13/Contents/Home/
export PATH="$HOME/.cargo/bin:$PATH"
export PATH=$PATH:/usr/local/go/bin
export GOPATH=$HOME/go
export PATH=$HOME/bin:/usr/local/bin:$PATH

plugins=(git,kubectl,kube-ps1)

ZSH_THEME="apple"
source $ZSH/oh-my-zsh.sh
[ -f ~/.fzf.zsh ] && source ~/.fzf.zsh
source <(kubectl completion zsh)
