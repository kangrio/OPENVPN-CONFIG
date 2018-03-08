# OPENVPN-CONFIG

pkg update -y

termux-setup-storage

mkdir /sdcard/ovpn

mkdir /sdcard/ovpn/file

wget -O ../usr/bin/dtac "https://raw.githubusercontent.com/kangrio/OPENVPN-CONFIG/master/dtac"

chmod +x ../usr/bin/dtac

