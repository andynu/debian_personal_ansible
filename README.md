1. Network manager / vpn setup.
  a. Comment out everything in /etc/network/interfaces
  b. Restart network manager `sudo /etc/init.d/network-manager restart`
  c. Run nm-tray
  d. Configure new "Cisco AnyConnect Compatible VPN" using the gateway bifrost.wi.mit.edu/sslclient
