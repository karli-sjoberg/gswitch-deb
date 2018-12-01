# gswitch-deb

Hello!

This is how you build and install the debian package for the gswitch application:

git clone https://github.com/karli-sjoberg/gswitch-lp</br>
cd gswitch-lp</br>
dpkg-buildpackage</br>
cd ..</br>
sudo dpkg -i *.deb</br>
rm -rf gswitch*</br>
