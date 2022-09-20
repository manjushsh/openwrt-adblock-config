
# Backup for OpenWRT configuration

This repo includes backup for OpenWRT router configuration. This will send report @12PM and 7PM and stores json to Amazon S3.




## Tool

[Flashable image with custom packages built with tool](https://firmware-selector.openwrt.org/)


## Packages

Remove `curl` if using `uclient-fetch` else remove `uclient-fetch` and use `curl`.

#### Other packages:

`base-files busybox ca-bundle dnsmasq dropbear firewall fstools ip6tables iptables kmod-gpio-button-hotplug kmod-ipt-offload kmod-leds-gpio kmod-mt7603 kmod-mt76x0e libc libgcc libustream-wolfssl logd mtd netifd odhcp6c odhcpd-ipv6only opkg ppp ppp-mod-pppoe procd swconfig uci uclient-fetch urandom-seed urngd wpad-basic-wolfssl luci tcpdump-mini msmtp adblock luci-app-adblock curl`



## Disclaimer

I'm not responsible for bricked devices, dead routers. 
Please do some research if you have any concerns about features included in the products you find here before flashing it! 
YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you. 
Your warranty will be void if you tamper with any part of your device / software.


