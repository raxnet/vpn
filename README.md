# Layanan VPN dengan Berbagai Protokol

![Logo VPN](https://github.com/raxnet/vpn/blob/main/nixy.jpg)

## Deskripsi

Proyek ini menyediakan layanan **VPN** yang dapat diinstal pada server Linux untuk meningkatkan keamanan dan privasi pengguna. Layanan yang tersedia meliputi berbagai protokol VPN dan proxy yang dapat dengan mudah dipasang dan dikonfigurasi.

## Sistem Operasi yang Didukung

Layanan ini mendukung beberapa distribusi Linux, termasuk:

- **Debian 9 (Stretch)**
- **Debian 10 (Buster)**
- **Ubuntu 18.04 LTS**
- **Ubuntu 20.04 LTS**

<p align="center">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=red" alt="Debian 9 Stretch">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=red" alt="Debian 10 Buster">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=18.04%20LTS&color=red" alt="Ubuntu 18.04 LTS">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=20.04%20LTS&color=red" alt="Ubuntu 20.04 LTS">
</p>

## Layanan VPN yang Tersedia

Berikut adalah layanan yang dapat Anda instal:

- **OpenSSH**
- **Dropbear**
- **BadVPN**
- **Stunnel**
- **OpenVPN**
- **Squid3**
- **Webmin**
- **Privoxy**
- **V2ray**
- **ShadowsocksR (SSR)**
- **Trojan**
- **WireGuard**

<p align="center">
  <img src="https://img.shields.io/badge/Service-OpenSSH-success.svg" alt="OpenSSH">
  <img src="https://img.shields.io/badge/Service-Dropbear-success.svg" alt="Dropbear">
  <img src="https://img.shields.io/badge/Service-BadVPN-success.svg" alt="BadVPN">
  <img src="https://img.shields.io/badge/Service-Stunnel-success.svg" alt="Stunnel">
  <img src="https://img.shields.io/badge/Service-OpenVPN-success.svg" alt="OpenVPN">
  <img src="https://img.shields.io/badge/Service-Squid3-success.svg" alt="Squid3">
  <img src="https://img.shields.io/badge/Service-Webmin-success.svg" alt="Webmin">
  <img src="https://img.shields.io/badge/Service-Privoxy-success.svg" alt="Privoxy">
  <img src="https://img.shields.io/badge/Service-V2ray-success.svg" alt="V2ray">
  <img src="https://img.shields.io/badge/Service-SSR-success.svg" alt="ShadowsocksR">
  <img src="https://img.shields.io/badge/Service-Trojan-success.svg" alt="Trojan">
  <img src="https://img.shields.io/badge/Service-WireGuard-success.svg" alt="WireGuard">
</p>

## Instruksi Instalasi dan Pembaruan

Untuk memulai dengan instalasi atau pembaruan, Anda dapat mengikuti langkah-langkah berikut:

### Instalasi Skrip

Jalankan perintah di bawah ini untuk menginstal skrip VPN:

```bash
apt update -y && apt upgrade -y && apt install -y wget lolcat && gem install lolcat
wget -q https://raw.githubusercontent.com/raxnet/vpn/main/install.sh
chmod +x install.sh
./install.sh
