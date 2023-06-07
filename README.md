# purpleyou
|  SERVICE  |  NETWORK PORT  |
|---------- |--------|
| Vmess WS TLS (multipath)  | 443 |
| Vless WS TLS  | 443 |
| Trojan WS TLS  | 443 |
| Vmess WS (multipath)  | 80 |
| Vless WS  | 80 |
| Trojan WS  | 80 |
| Vmess gRPC  | 443 |
| Vless gRPC  | 443 |
| Trojan gRPC  | 443 |
| Auto Delete Expired Account | ✅ |

|  ALTERNATIF PORT  |  NETWORK PORT  |
|-------------------|--------|
| HTTPS  | 2053, 2083, 2087, 2096, 8443 |
| HTTP  | 8080, 8880, 2052, 2082, 2086, 2095 |


<font color="red"><b>Update Repo Khusus Debian 10 <br>

  

  ```html

apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot

  ```

  

Update Repo Khusus Ubuntu 18/20 <br>

  

  ```html

apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot

 ```

Perintah Install Copas ke Vps Mu<br>

  ```html

apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/zenvpn/xrayv1/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh

```
