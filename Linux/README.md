Sample code to get GEO location data for Linux 

```
sudo apt install meson
sudo apt install modemmanager-dev
sudo apt install libavahi-client-dev
sudo apt install libavahi-glib-dev
sudo apt install libnotify-dev

sudo apt install libjson-glib-dev
sudo apt install libsoup-3.0-dev
sudo apt install libmm-glib-dev
sudo apt install libgirepository1.0-dev
sudo apt install valac
sudo apt install gettext
sudo apt install gtk-doc-tools

cd geoclue
meson --prefix=/usr --sysconfdir /etc -Ddbus-srv-user=geoclue build

ninja -C build
sudo ninja -C build install
```

```
cat /etc/passwd | grep "geoclue"
sudo chsh geoclue -s /bin/bash
```
```
sudo cp config/geoclue.conf /etc/geoclue/geoclue.conf
```
```
sudo systemctl restart geoclue
sudo systemctl daemon-reload
```
```
# sudo apt install libgeoclue-2-dev libgeoclue-2-0 libdbus-1-dev libglib2.0-dev make gcc
cd ..
make
./getlocation(sudo ./getlocation)
```
<!---
spictera/spictera is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
