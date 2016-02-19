# wifi-utils

WiFi Command Line Utilities for Ubuntu Distros

## Install

    $ npm install --global https://github.com/bencevans/wifi-utils.git

## Usage

* [wifi-ssid](#wifi-ssid)
* [wifi-password](#wifi-password)
* [wifi-ifconfig](#wifi-ifconfig)
* [wifi-ip](#wifi-ip)

### wifi-ssid

With WiFi Connected

    $ wifi-ssid
    mycurrentwirelessssid

With WiFi Disconnected (Exit Code=1)

    $ wifi-ssid
    No Active WiFi Network

### wifi-password

With WiFi Connected

    $ wifi-password
    likeimputtingthatinareadme

With WiFi Disconnected (Exit Code=1)

    $ wifi-password
    No Active WiFi Network

### wifi-ifconfig

With WiFi Connected - Ouputs ifconfig for found WiFi device

    $ wifi-ifconfig
    wlp58s0   Link encap:Ethernet  HWaddr 30:52:cb:e7:a4:c5
              inet addr:192.168.1.20  Bcast:192.168.1.255  Mask:255.255.255.0
              inet6 addr: fe80::3252:cbff:fee7:a4c5/64 Scope:Link
              UP BROADCAST RUNNING MULTICAST  MTU:1500  Metric:1
              RX packets:381464 errors:0 dropped:19 overruns:0 frame:0
              TX packets:290123 errors:0 dropped:0 overruns:0 carrier:0
              collisions:0 txqueuelen:1000
              RX bytes:346635228 (346.6 MB)  TX bytes:34510702 (34.5 MB)

With WiFi Disconnected (Exit Code=1)

    $ wifi-ifconfig
    No Active WiFi Network

### wifi-ip

With WiFi Connected

    $ wifi-ip
    192.168.1.20

With WiFi Disconnected (Exit Code=1)

    $ wifi-ip
    No Active WiFi Network

## Licence

ISC
