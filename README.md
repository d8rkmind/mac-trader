<img src="https://img.shields.io/badge/Python-3-brightgreen.svg?style=plastic">
# Mac-trader

MAC spoofing is a technique for modifying a network interface's factory-assigned Media Access Control address on a networked deviceThis can be accomplished with mac - traders, a python3 script capable of initiating a MAC spoofing operation, which involves modifying the MAC address of the specified  network device as the argument.

### Installation:

```
git clone https://github.com/d8rkmind/mac-trader.git
chmod +x mac-trader
```
### Usage:
```
sudo ./mac-trader -i <interface name> -m <specific mac address>
                    or
sudo ./mac-trader -i <interface name> -r
```
flags | uses
------|-----
-i|to specify interface card
-m|to give a specific mac address 
-r|to give a random mac address


#### Example:
```
sudo ./mac-trader -i wlan0 -m 00:00:00:22:33:11
                 or
sudo ./mac-trader -i wlan0 -r
```

 
 
