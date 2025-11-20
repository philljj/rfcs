## Description

Got tired of tracking and redownloading RFCs.

## Usage

```
[rfcs]$ls
clean_em  get_ipsec  get_tls  get_x509  README.md

[rfcs]$./get_ipsec 
rfc3948.txt          100% [===================================>]    8.35K    --.-KB/s
                          [Files: 1  Bytes: 8.35K [35.69KB/s] R]
rfc4106.txt          100% [===================================>]    7.14K    --.-KB/s
                          [Files: 1  Bytes: 7.14K [24.99KB/s] R]
rfc4303.txt          100% [===================================>]   29.42K    3.70MB/s
                          [Files: 1  Bytes: 29.42K [114.48KB/s]]
rfc4543.txt          100% [===================================>]    8.50K    --.-KB/s
                          [Files: 1  Bytes: 8.50K [31.48KB/s] R]

[rfcs]$ls
clean_em   get_tls   README.md    rfc4106.txt  rfc4543.txt
get_ipsec  get_x509  rfc3948.txt  rfc4303.txt

[rfcs]$./clean_em 

[rfcs]$ls
clean_em  get_ipsec  get_tls  get_x509  README.md
```
