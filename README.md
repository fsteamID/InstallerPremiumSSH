![Personal VPS](https://shields.io/badge/Personal-VPS-orange?logo=jamboard&style=for-the-badge) ![OS](https://camo.githubusercontent.com/c267217ffbbe2bcd687eaeef3aa9a1b83d72bf1a494635856b720c6a19944bcb/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d44656269616e26636f6c6f723d413831443333266c6f676f3d44656269616e266c6f676f436f6c6f723d464646464646266c6162656c3d) ![Free Licence](https://shields.io/badge/Free-Licence-orange?logo=testinglibrary&style=for-the-badge) ![Auto Reboot](https://shields.io/badge/Auto-Reboot-orange?logo=openapiinitiative&style=for-the-badge) ![Xray](https://shields.io/badge/Service-Xray-orange?logo=xstate&style=for-the-badge)
![Virtualization](https://shields.io/badge/Virtualization-KVM-green?logo=tryhackme&style=for-the-badge) ![Architecture](https://shields.io/badge/Architecture-Intel%20or%20AMD-green?logo=moleculer&style=for-the-badge)

### Service & Port:

Service Port

- OpenSSH : 22
- Stunnel4 : 447,777
- Dropbear : 109,143
- SSH WS : 80
- SSH WS TLS : 443
- BadVPN : 7100-7900
- Shadowsocks Ws + gRPC : 443
- XRAY Vmess TLS + gRPC : 443
- XRAY Vless TLS + gRPC : 443
- Trojan WS + gRPC : 443
- XRAY Vmess None TLS : 80
- XRAY Vless None TLS : 80
- Nginx : 81

### Fitur

Server Information & Other Features

- Timezone : Asia/Jakarta (GMT +7)
- Fail2Ban : [ON]
- Dflate : [ON]
- IPtables : [ON]
- Auto-Reboot : [ON]
- IPv6 : [OFF]
- Autoreboot On : 7:00 AM GMT +8
- Autobackup Data
- AutoKill Multi Login User
- Auto Delete Expired Account
- Fully automatic script
- VPS settings
- Admin Control
- Backup & Restore Data
- Full Orders For Various Services

### Other Services:

Speedtest CLI

### Syarat VPS

- Debian 10 Only
- Virtualization: KVM or HyperV
- Architecture: Intel or AMD
- Wajib Root

### Installation

Copy dan paste code di bawah ke dalam terminal lalu tekan enter.

Update Repo Debian 10

```html
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
```

Perintah Install Copas ke Vps Mu<br>

```html
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/fsteamID/InstallerPremiumSSH/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```


# InstallerPremiumSSH
