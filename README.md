**Free vpn, tor, datacenter, threat detection by IP address**

### Install

```bash
pip indtall detectvpn
```

### How to use

```python
# Detect vpn, tor, datacenter, threat on IP
>>> from detectvpn import detect
>>> detect.ip("8.8.8.8")
normal
>>>

```

### Detection info

```
vpn        - using vpn
tor        - using tor
datacenter - its datacenter IP
threat     - dangerous IP
normal     - normal IP address
```
