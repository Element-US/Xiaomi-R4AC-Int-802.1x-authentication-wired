# Xiaomi-R4AC-Int-802.1x-authentication-wired
Image created for the router with the following specifications, having added all the modules for the 802.1x authentication wired connection
# OpenWrt firmware for Xiaomi Mi Router 4A (R4AC)

It is for sysupgrade, contains modules for 802.1x connection via wire

## Technical data

[OpenWrt TechData](https://openwrt.org/toh/hwdata/xiaomi/xiaomi_r4ac_international_100m)
[DevWiki TechData](https://deviwiki.com/wiki/Xiaomi_Mi_Router_4A_100M_(R4AC))

## Installation

Using the upgrade option from openwrt


## Installed modules

base-files - 1498-r20028-43d71ad93e\
busybox - 1.35.0-5\
ca-bundle - 20211016-1\
cgi-io - 2022-08-10-901b0f04-21\
dnsmasq - 2.86-15\
dropbear - 2022.82-2\
firewall4 - 2022-10-18-7ae5e14b-1\
fstools - 2022-06-02-93369be0-2\
fwtool - 2019-11-12-8f7fe925-1\
getrandom - 2021-08-03-205defb5-2\
hostapd-common - 2022-01-16-cff80b4f-15.2\
iw - 5.16-1\
iwinfo - 2022-12-15-8d158096-1\
jansson4 - 2.13.1-2\
jshn - 2022-05-15-d2223ef9-1\
jsonfilter - 2018-02-04-c7e938d6-1\
kernel - 5.10.161-1-8bb071fd201e2499888328d82fbc70db\
kmod-cfg80211 - 5.10.161+5.15.81-1-1\
kmod-crypto-aead - 5.10.161-1\
kmod-crypto-ccm - 5.10.161-1\
kmod-crypto-cmac - 5.10.161-1\
kmod-crypto-crc32c - 5.10.161-1\
kmod-crypto-ctr - 5.10.161-1\
kmod-crypto-gcm - 5.10.161-1\
kmod-crypto-gf128 - 5.10.161-1\
kmod-crypto-ghash - 5.10.161-1\
kmod-crypto-hash - 5.10.161-1\
kmod-crypto-hmac - 5.10.161-1\
kmod-crypto-manager - 5.10.161-1\
kmod-crypto-null - 5.10.161-1\
kmod-crypto-rng - 5.10.161-1\
kmod-crypto-seqiv - 5.10.161-1\
kmod-crypto-sha256 - 5.10.161-1\
kmod-gpio-button-hotplug - 5.10.161-3\
kmod-leds-gpio - 5.10.161-1\
kmod-lib-crc-ccitt - 5.10.161-1\
kmod-lib-crc32c - 5.10.161-1\
kmod-mac80211 - 5.10.161+5.15.81-1-1\
kmod-mt76-core - 5.10.161+2022-09-06-d7054646-5\
kmod-mt7603 - 5.10.161+2022-09-06-d7054646-5\
kmod-mt76x02-common - 5.10.161+2022-09-06-d7054646-5\
kmod-mt76x2 - 5.10.161+2022-09-06-d7054646-5\
kmod-mt76x2-common - 5.10.161+2022-09-06-d7054646-5\
kmod-nf-conntrack - 5.10.161-1\
kmod-nf-conntrack6 - 5.10.161-1\
kmod-nf-flow - 5.10.161-1\
kmod-nf-log - 5.10.161-1\
kmod-nf-log6 - 5.10.161-1\
kmod-nf-nat - 5.10.161-1\
kmod-nf-reject - 5.10.161-1\
kmod-nf-reject6 - 5.10.161-1\
kmod-nfnetlink - 5.10.161-1\
kmod-nft-core - 5.10.161-1\
kmod-nft-fib - 5.10.161-1\
kmod-nft-nat - 5.10.161-1\
kmod-nft-offload - 5.10.161-1\
kmod-ppp - 5.10.161-1\
kmod-pppoe - 5.10.161-1\
kmod-pppox - 5.10.161-1\
kmod-slhc - 5.10.161-1\
libblobmsg-json20220515 - 2022-05-15-d2223ef9-1\
libc - 1.2.3-4\
libgcc1 - 11.2.0-4\
libiwinfo-data - 2022-12-15-8d158096-1\
libiwinfo-lua - 2022-12-15-8d158096-1\
libiwinfo20210430 - 2022-12-15-8d158096-1\
libjson-c5 - 0.15-2\
libjson-script20220515 - 2022-05-15-d2223ef9-1\
liblua5.1.5 - 5.1.5-10\
liblucihttp-lua - 2022-07-08-6e68a106-1\
liblucihttp0 - 2022-07-08-6e68a106-1\
libmnl0 - 1.0.5-1\
libnftnl11 - 1.2.1-2\
libnl-tiny1 - 2021-11-21-8e0555fb-1\
libopenssl1.1 - 1.1.1t-1\
libpthread - 1.2.3-4\
libubox20220515 - 2022-05-15-d2223ef9-1\
libubus-lua - 2022-06-01-2bebf93c-1\
libubus20220601 - 2022-06-01-2bebf93c-1\
libuci20130104 - 2021-10-22-f84f49f0-6\
libuclient20201210 - 2021-05-14-6a6011df-1\
libucode20220812 - 2022-12-02-46d93c9c-1\
libustream-wolfssl20201210 - 2022-12-08-9217ab46-2\
libwolfssl5.5.4.ee39414e - 5.5.4-stable-1\
logd - 2021-08-03-205defb5-2\
lua - 5.1.5-10\
luci - git-20.074.84698-ead5e81\
luci-app-cd8021x - 1.2.1-1\
luci-app-firewall - git-22.089.67563-7e3c1b4\
luci-app-opkg - git-22.273.29004-9f6876b\
luci-base - git-23.069.50944-cd8bea9\
luci-compat - git-22.069.45071-03bb0e2\
luci-lib-base - git-20.232.39649-1f6dc29\
luci-lib-ip - git-20.250.76529-62505bd\
luci-lib-jsonc - git-22.097.61921-7513345\
luci-lib-nixio - git-20.234.06894-c4a4e43\
luci-mod-admin-full - git-19.253.48496-3f93650\
luci-mod-network - git-22.345.48602-4853e7b\
luci-mod-status - git-23.038.33313-b256644\
luci-mod-system - git-23.013.73113-588381e\
luci-proto-ipv6 - git-21.148.48881-79947af\
luci-proto-ppp - git-21.158.38888-88b9d84\
luci-theme-bootstrap - git-22.288.45147-96ec0cd\
mtd - 26\
netifd - 2022-08-25-76d2d41b-1\
nftables-json - 1.0.2-2.1\
odhcp6c - 2022-08-05-7d21e8d8-18\
odhcpd-ipv6only - 2023-01-02-4a673e1c-2\
openwrt-keyring - 2022-03-25-62471e69-3\
opkg - 2022-02-24-d038e5b6-1\
ppp - 2.4.9.git-2021-01-04-3\
ppp-mod-pppoe - 2.4.9.git-2021-01-04-3\
procd - 2022-06-01-7a009685-2\
procd-seccomp - 2022-06-01-7a009685-2\
procd-ujail - 2022-06-01-7a009685-2\
rpcd - 2022-12-15-7de4820c-1\
rpcd-mod-file - 2022-12-15-7de4820c-1\
rpcd-mod-iwinfo - 2022-12-15-7de4820c-1\
rpcd-mod-luci - 20210614\
rpcd-mod-rrdns - 20170710\
swconfig - 12\
ubox - 2021-08-03-205defb5-2\
ubus - 2022-06-01-2bebf93c-1\
ubusd - 2022-06-01-2bebf93c-1\
uci - 2021-10-22-f84f49f0-6\
uclient-fetch - 2021-05-14-6a6011df-1\
ucode - 2022-12-02-46d93c9c-1\
ucode-mod-fs - 2022-12-02-46d93c9c-1\
ucode-mod-ubus - 2022-12-02-46d93c9c-1\
ucode-mod-uci - 2022-12-02-46d93c9c-1\
uhttpd - 2022-10-31-23977554-1\
uhttpd-mod-ubus - 2022-10-31-23977554-1\
urandom-seed - 3\
urngd - 2020-01-21-c7f7b6b6-1\
usign - 2020-05-23-f1f65026-1\
wireless-regdb - 2022.08.12-1\
wpad-openssl - 2022-01-16-cff80b4f-15.2\


## License

Created to be shared and used
