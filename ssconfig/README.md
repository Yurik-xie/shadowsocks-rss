## Install ##

    pip install shadowsocks 
    
    
## Usage ##

    sslocal -c example.json


## Tools ##

### proxychains ###

Modify 

    /etc/proxychains.conf

add: 

    socks5 127.0.0.1 1080

usage:

    proxychains <command>
