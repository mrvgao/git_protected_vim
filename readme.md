Safer VIM for git

# Why you need this?

This will make you can not modify any file in **git master** branch.

# How To Use That?

1. Clone the file to your *any path*, in this readme, I will put this file in my home/bin.

2. and change the new_vim mode
```bash
$chmod 755 new_viw
```

3. set $PATH in your .bash_profile or .zshrc(if you use zsh)
```bash
export PATH=$PATH:/Users/develop/bin
```

4. set alise 
```bash
alias vi='new_vi'
```
