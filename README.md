# gswitch-deb

Hello!

This is how you build and install the debian package for the gswitch application:

git clone https://github.com/karli-sjoberg/gswitch-deb</br>
cd gswitch-deb</br>
dpkg-buildpackage</br>
cd ..</br>
sudo dpkg -i \*.deb</br>
rm -rf gswitch\*</br>

sudo gswitch setup

This package also comes with automatic detection of eGPU at boot!

After gswitch has been configured and you've got the switching set up, simply
run 'systemctl enable gswitch' and it will configure the eGPU automatically
when you boot. It will also also switch back to internal if you've by accident
forgotten to switch back to internal when leaving home and found yourself stuck
at a black screen; no more!

Yeah, that happened once too many ;)
