Deploy vim_config project
=========================
Install pathogen
---------------
```sh
mkdir -p ~/.vim/autoload ~/.vim/bundle
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
Install NERDTree
----------------
```sh
cd ~/.vim/bundle
git clone https://github.com/scrooloose/nerdtree.git
```
Install NERDTree tabs
---------------------
```sh
cd ~/.vim/bundle
git clone https://github.com/jistr/vim-nerdtree-tabs.git
```
Install Airline
---------------
```sh
git clone https://github.com/vim-airline/vim-airline ~/.vim/bundle/vim-airline
```
Install Syntastic
-----------------
```sh
cd ~/.vim/bundle && \
git clone https://github.com/scrooloose/syntastic.git
```
Setup .vimrc file
-----------------
```sh
cp ~/.vimrc ./vimrc.bak
cp ./vimrc.txt ~/.vimrc
```