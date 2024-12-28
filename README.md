# Pengaturan Layanan VPN

<div align="center">
  <img src="https://github.com/raxnet/vpn/blob/main/nixy.jpg" alt="Gambar Pengaturan VPN" />
</div>

## Animasi Instalasi

Berikut adalah animasi langkah-langkah instalasi layanan VPN:

<div align="center">
  <img src="https://media.giphy.com/media/xT0GqQIfjHF5xXjP9e/giphy.gif" alt="Instalasi VPN" />
</div>

## Sistem Operasi yang Didukung

Layanan VPN ini mendukung berbagai distribusi sistem operasi berbasis Linux, termasuk:

<p align="center">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209%20&%202010&message=Stretch&color=red" alt="Debian 9 Stretch">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=red" alt="Debian 10 Buster">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=18.04%20LTS&color=red" alt="Ubuntu 18.04 LTS">
  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=20.04%20LTS&color=red" alt="Ubuntu 20.04 LTS">
</p>

## Layanan yang Tersedia

Proyek ini mendukung berbagai layanan VPN dan proxy yang dapat diinstal dan dikonfigurasi dengan mudah:

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

## Perintah Instalasi dan Pembaruan

Untuk menginstal semua layanan VPN yang tersedia sekaligus dan melakukan pembaruan otomatis, jalankan perintah berikut:

```bash
apt install -y && apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && wget -q https://raw.githubusercontent.com/raxnet/vpn/main/install.sh && chmod +x install.sh && ./install.sh && wget https://raw.githubusercontent.com/raxnet/vpn/main/update.sh && chmod +x update.sh && ./update.sh
