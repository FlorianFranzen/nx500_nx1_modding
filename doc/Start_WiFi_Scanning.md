#Starting WiFi scanning

*Currently only tested on NX500*

In order to start wifi scan one needs to write following byte sequence to 

  - file: **/tmp/var/run/memory/ap_setting/request_type**
  - bytes: **0x2900000001000000**
