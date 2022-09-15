# Setup vim editor as a python ide on a linux system

## Requirement :

**Install Python3 and vim editor**

*For Ubuntu* :
```bash
	sudo apt install python3 python3-pip vim
```
## Run The code :

1. Clone the repository
```bash
    git clone https://github.com/sumony2j/My-Python_IDE.git
```
2. Clone VundleVim
```bash
    git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
3. Go to directory
```bash
    cd My-Python_IDE
```
4. Copy the content of vimrc file to ~/.vimrc
```
    cp ./vimrc ~/.vimrc
```
5. Run
```bash
    vim +PluginInstall +qall
```
## View 

![sample1](https://user-images.githubusercontent.com/64437345/186928774-0237a2a6-3daa-4b32-a48a-201712113733.png)

![sample2](https://user-images.githubusercontent.com/64437345/186928839-41d39f34-f10f-4da6-8bfc-9c1692dc8f6c.png)

![sample3](https://user-images.githubusercontent.com/64437345/186928924-717d42c6-a5d2-407f-b6f3-4e4ae987e43b.png)


## Note :

To add more plugins follow the steps :

1. Add the new plugin before **call vundle#end()** with the following syntax in ~/.vimrc file -
```
    Plugin '<name of plugin>'
```
2. save and exit the ~/.vimrc file

3. In terminal run the following command :
```
    vim +PluginInstall +qall
```
