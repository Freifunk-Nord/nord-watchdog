# nord-watchdog

`vpn-watchdog` checks if it can reach several `destination_ip`s with

    ping -q -I tun-anonvpn -c1 -m 1 $destination_ip

if not it restarts openvpn with

    service openvpn restart


#Source:
https://forum.freifunk.net/t/script-das-vpn-auf-einem-gateway-ueberwacht-und-ggf-wieder-startet/9651/
