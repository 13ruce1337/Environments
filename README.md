# Environments
Assorted run commands and confuration files

## Bash
`alias ll='ls -alF'`  
`alias la='ls -A'`  
`alias l='ls -CF'`  

## VIM
[Vundle](https://github.com/vundlevim/vundle.vim) - Package manager for vim plugins  
[YouCompleteMe](https://github.com/ycm-core/YouCompleteMe) - Auto completion   
[Markdown Preview](https://github.com/iamcco/markdown-preview.nvim) - Previews MD in browser  
[SimpylFold](https://github.com/tmhedberg/SimpylFold) - folds/carrots lines of code into 1  

### Vundle
This repo is currently down.  
https://www.reddit.com/r/vim/comments/11890p5/the_vundle_github_repo_seems_to_have_disappeared/

### YouCompleteMe
```
cd ~/.vim/bundle/YouCompleteMe
python3 install.py --all
```

### Markdown Preview
```
:source %
:PluginInstall
:call mkdp#util#install()
```

### SimpylFold
`zo` to open a fold
`zc` to close a fold
`:help fold-commands` for full documentation
