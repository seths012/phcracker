<h1 align="center"> VPN AutoScript Debian Stretch<img src="https://img.shields.io/badge/Version-2.1-blue.svg"></h1>

<p align="center">VPN AutoScript is made by Badbox to minimize the time consumed and user involvement in setting up your VPS</p>
<p align="center">[Donations] GCASH: 09099027322 WEBSITE: www.phcracker.net FACEBOOK: http://facebook.com/phcracker.net</p>

<h3 align="center">Supported Linux Distribution</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Support-Debian%209-red.svg"></a>
  
</p>
<h3 align="center">Services</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Service-OpenSSH-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Dropbear-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Stunnel-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-OpenVPN-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-Squid3-green.svg"></a>
  <a><img src="https://img.shields.io/badge/Service-ShadowsocksR-green.svg"></a>
 </p>
<h3 align="center">Commands</h3>
<p align="center">
  <a><img src="https://img.shields.io/badge/Commands-menu-yellow.svg"></a>
 </p>

<h3 align="center">Installation (DigitalOcean, VULTR & MNX Solutions)</h3>

  ```html
wget https://raw.githubusercontent.com/phcu-badbox/phcracker/master/DebianStretch && chmod +x DebianStretch && ./DebianStretch
  ```
<h3 align="center">Installation (N Version)</h3>

  ```html
wget https://raw.githubusercontent.com/phcu-badbox/phcracker/master/DebianStretchN && chmod +x DebianStretchN && ./DebianStretchN
  ```

<h3 align="center">Installation (Dropbear Port 443)</h3>

  ```html
wget https://raw.githubusercontent.com/phcu-badbox/phcracker/master/DebianStretchD && chmod +x DebianStretchD && ./DebianStretchD
  ```

<h3 align="center">Installation LEMP Stack Webserver</h3>

  ```html
wget https://raw.githubusercontent.com/phcu-badbox/phcracker/master/LEMP7 && chmod +x LEMP7 && ./LEMP7
  ```


<h3 align="center">Additional Info</h3>
<p align="center">
Recommended OS: Debian 9 Stretch x64


   <h3 align="center">ShadowsocksR (Optional)</h3>
   <p align="left">
   Download (Android): https://github.com/shadowsocksr-backup/shadowsocksr-android/releases
  
   Download (Windows): https://github.com/shadowsocksr-backup/shadowsocksr-csharp/releases
  
   Configuration file path: /etc/shadowsocks.json 
   
   Log file path: /var/log/shadowsocks.log 
   
   Installation directory: /usr/local/shadowsocks
   
   
   Installation:
   
```html
wget --no-check-certificate https://raw.githubusercontent.com/phcu-badbox/phcracker/master/ShadowR.sh
chmod +x ShadowR.sh
./ShadowR.sh 2>&1 | tee shadowsocksR.log
```
   Commands:
```html
Start: /etc/init.d/shadowsocks start 
Stop: /etc/init.d/shadowsocks stop 
Restart: /etc/init.d/shadowsocks restart 
Status: /etc/init.d/shadowsocks status
```

   Multi User Config Setup:
```html
{
"server":"0.0.0.0",
"server_ipv6": "[::]",
"local_address":"127.0.0.1",
"local_port":1080,
"port_password":{
    "8989":"password1",
    "8990":"password2",
    "8991":"password3"
},
"timeout":300,
"method":"aes-256-cfb",
"protocol": "origin",
"protocol_param": "",
"obfs": "plain",
"obfs_param": "",
"redirect": "",
"dns_ipv6": false,
"fast_open": false,
"workers": 1
}
```

Website Support: https://www.phcracker.net
   </p>
