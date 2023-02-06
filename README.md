# MyVimrc
## vim-plug

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

## YcmComplete

```bash
cd ~/.vim/plugged/youcompleteme/

sudo apt install build-essential cmake vim python3-dev -y

sudo apt install mono-complete golang nodejs npm -y

git submodule update --init --recursive

python3 install.py --all
```