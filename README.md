# calendar-applet
A budgie-desktop applet to show hours and when click show a calendar in a popover


## Dependencies
```
vala
gtk+-3.0
gio-unix-2.0
libpeas-1.0
PeasGtk-1.0
budgie-1.0
```

These can be installed on Solus by running:  
```
sudo eopkg it vala libgtk-3-devel glib2-devel libpeas-devel budgie-desktop-devel
```

### Installing
```
./autogen.sh --prefix=/usr
make -j$(($(getconf _NPROCESSORS_ONLN)+1))
sudo make install
```

### Screenshot
![Screenshot](screenshot.png)
