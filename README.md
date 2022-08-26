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
2. Copy the content of vimrc file to ~/.vimrc
```
    cp ./vimrc ~/.vimrc
```
## View 

![Alt text](./img/sample1.png,"Sample View")

![Alt text](./img/sample2.png,"Sample View")

![Alt text](./img/sample3.png,"Sample View")

## Note :

To add more plugins follow the steps :

1. Add the new plugin before **call vundle#end()** with the following syntax -
```
    Plugin '<name>'
```
2. save and exit the ~/.vimrc file

3. In terminal run the following command :
```
    vim +PluginInstall +qall
```
