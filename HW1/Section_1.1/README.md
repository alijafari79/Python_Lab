We have 3 types of connections through VMware that can be connected to the network:

1. [Host-only](https://github.com/alijafari79/Python_Lab/blob/main/HW1/Section_1.1/README.md#host-only)
2. NAT
3. Bridged

## Host-only
**Host-only** only permits network operations with the Host OS. The VM will be assigned one IP, but it's only accessible by the box VM is running on. No other computers can access it. When set to host only, the VM exists only on a private network visible to other VMs on the same host using the same setting, and to the host machine itself, but no connection is available from the VM to external networks via the host adapter.

## NAT
**NAT** mode will mask all network activity as if it came from your Host OS, although the VM can access external resources. Just like your home network with a wireless router, the VM will be assigned in a separate subnet, like `192.168.6.1` is your host computer, and VM is `192.168.6.3`, then your VM can access outside network like your host, but no outside access to your VM directly, it's protected. When set to NAT, the host system acts like a router in that the traffic from the VM appears to come from the IP address of the host system itself. Incoming traffic is routed to the VM only if port forwarding is created, or if it is in response to a prior outbound request from the VM.

## Bridged
**Bridged** mode replicates another node on the physical network and your VM will receive its own IP address if DHCP is enabled in the network. Your VM will be in the same network as your host, if your host IP is `172.16.120.45` then your VM will be like `172.16.120.50`. It can be accessed by all computers in your host network. When set to “bridged”, the VM gets its own IP address and appears to be a completely distinct machine on the network even though its traffic passes through the host adapter.
