# gswitch-deb

Hello!

This is how you build and install the debian package for the gswitch application:

git clone https://github.com/karli-sjoberg/gswitch-deb</br>
cd gswitch-deb</br>
dpkg-buildpackage</br>
cd ..</br>
sudo dpkg -i \*.deb</br>
rm -rf gswitch\*</br>
