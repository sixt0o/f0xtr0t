# f0xtr0t - pwnagotchi plugin

Based on the original webgpsmap plugin, f0xtr0t is an enhanced version that gives you an interfaced optimized for wardriving. With a fully responsive design, you can easily view on your phone, tablet, or even a 4.5 inch pi touchscreen. For the best experience, it's recommended that you have your pwnagotchi tethered (BT/Wifi/Ethernet) to an Internet connection with a GPSD compatible device running.


# Config
main.plugins.f0xtr0t:
 - enabled: true
 - gpsprovider: "gpsd" or "pawgps"
 - gpsdhost: "127.0.0.1"
 - gpsdport: 2947
 - pawgpshost: "http://192.168.44.1:8080/gps.xhtml"
