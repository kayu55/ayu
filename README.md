
# UP REPO DEBIAN
<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot</code></pre>
# UP REPO UBUNTU
<pre><code>apt update && apt upgrade -y && update-grub && sleep 2 && reboot</pre></code>

````
wget -O dirmeluna "raw.githubusercontent.com/kayu55/ayu/main/configure/dirmeluna.sh" && chmod +x dirmeluna
````

### INSTALL SCRIPT 
<pre><code>wget -q https://raw.githubusercontent.com/kayu55/ayu/main/setup.sh && chmod +x setup.sh && ./setup.sh
</code></pre>

### TESTED ON OS 
- UBUNTU 20,22,24
- DEBIAN 10,11,12

### PORT INFO
```
- TROJAN WS  443 8443
- TROJAN GRPC 443 8443
- SHADOWSOCKS WS 443 8443
- SHADOWSOCKS GRPC 443 8443
- VLESS WSS 443 8443
- VLESS GRPC 443 8443
- VLESS NONTLS 80 8080 8880 2082
- VMESS WS 443 8443
- VMESS GRPC 443 8443
- VMESS NONTLS 80 8080 8880 2082
- SSH WS / TLS 443 8443
- SSH NON TLS 8880 80 8080 2082 2095 2086
- OVPN SSL/TCP 1194
- SLOWDNS 5300
```
