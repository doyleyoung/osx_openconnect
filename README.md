# osx_openconnect
Couple scripts that make living with Cisco AnyConnect VPNs tolerable.

These scripts assume you have installed [openconnect](ihttp://www.infradead.org/openconnect/) and have it working correctly. For me that went something like

 * brew install openconnect
 * brew install Caskroom/cask/tuntap

Create a config file and add it's path to start_vpn where it says /path/to/config/vpn.conf. It
should have entries like (man openconnect for other options):

```
user=username
authgroup=AnyConnectAuthGroup
```

Modify start_vpn and add your VPN server name where it says \*your.server.name\*.
