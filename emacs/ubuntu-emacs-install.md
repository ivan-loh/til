This is how you can install emacs24 from the source

```sh
sudo apt-get install build-essential
sudo apt-get build-dep emacs24
wget http://ftp.gnu.org/gnu/emacs/emacs-24.5.tar.gz
tar xvzf emacs-24.5.tar.gz
cd emacs-24.5
./configure
make
sudo make install
```
