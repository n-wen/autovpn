## AUTOVPN ##

### USAGE ###

> sudo autovpn --config your.ovpn --ip http://youripserver.com/ip

### PREREQUISITES ###

1. openvpn client:  brew install openvpn

2. somewhere to get your openvpn server ip address by http, like:  curl http://youripserver.com/ip  >   100.8.8.8


### INSTALL ###

> pip install git+https://github.com/htwenning/autovpn.git

### UNINSTALL ###

> pip uninstall autovpn
