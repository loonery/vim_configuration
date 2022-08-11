This repository houses a set of vim configuration settings that I use to make Vim feel a bit more like an IDE when I am working with C! The settings are commented and can be reconfigured as needed. The colorscheme is called "everforest" : https://github.com/sainnhe/everforest. 


CODE FOLDING-----------------------------------------------------------------------------------------------------------
Code folding is not enjoyed by everyone. To disable the code folding (After following installation steps), navigate to the path ".vim/after/ftplugin/" and remove the file "c.vim" that dictates code folding behavior.




INSTALLATION -----------------------------------------------------------------------------------------------------------
1) clone this repository to your home directory
2) move .vimrc to your home directory
3) The cloned directory "vim_configuration" should be renamed to ".vim" and stored in your HOME ~ directory.
4) Open .vimrc in vim and while in Normal mode type ":PlugInstall" to the vim command line to install plugins (NerdTree and ALE).
