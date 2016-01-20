Custom LaTeX packages and classes
=================================

Setup
-----
Works on Ubuntu 14.04 with its TeX Live distribution
~~~
cd $HOME
git clone https://github.com/mschrode/.texmf.git
sudo echo "TEXMFHOME=$HOME/.texmf" > /etc/texmf/texmf.d/home.cnf
sudo texhash
sudo update-texmf
~~~