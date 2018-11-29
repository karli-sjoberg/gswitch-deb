# gswitch-deb

Hello!

This is how you build the debian package for the gswitch application:

git clone https://github.com/karli-sjoberg/gswitch</br>
git clone https://github.com/karli-sjoberg/gswitch-deb</br>
rm gswitch-deb/gswitch/usr/local/bin/place_gswitch_binary_here</br>
rm gswitch-deb/gswitch/etc/X11/place_xorg_template_here</br>
cp gswitch/gswitch gswitch-deb/gswitch/usr/local/bin/</br>
chmod +x gswitch-deb/gswitch/usr/local/bin/gswitch</br>
cp gswitch/xorg.conf.egpu gswitch-deb/gswitch/etc/X11/</br>
cd gswitch-deb</br>
sudo chown -R root:root gswitch</br>
sudo dpkg-deb --build gswitch</br>
sudo dpkg -i gswitch.deb
