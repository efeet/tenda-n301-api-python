# tenda-n301-api
Unofficial Tenda Model N301 API


```
import tendan301api

manager = tendan301api.TendaManager('<ip_address>', '<your_password>')

# Get QOS
online_devices = manager.get_online_devices()
blocked_devices = manager.get_black_list()

# Set QOS
manager.block_device('<some_mac_address>')
```