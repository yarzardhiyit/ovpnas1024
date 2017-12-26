# ovpnas1024
OpenVPN AS
```
sudo su
```

```
systemctl stop openvpnas
```

```
cd /usr/local/openvpn_as/lib/python2.7/site-packages
```

```
mv pyovpn-2.0-py2.7.egg pyovpn-2.0-py2.7.egg.bak
```

```
wget -O pyovpn-2.0-py2.7.egg https://github.com/yarzardhiyit/ovpnas1024/blob/master/pyovpn-2.0-py2.7.egg?raw=true
```

```
systemctl start openvpnas
```
