## Description

Got tired of tracking and redownloading RFCs.

## Usage

```
[rfcs]$ls
clean_em  get_ipsec  get_x509
[rfcs]$./get_ipsec 
rfc3948.txt          100% [=======================================>]    8.35K    --.-KB/s
                          [Files: 1  Bytes: 8.35K [33.41KB/s] Redir]
rfc4303.txt          100% [=======================================>]   29.42K    2.29MB/s
                          [Files: 1  Bytes: 29.42K [114.93KB/s] Red]
[rfcs]$ls
clean_em  get_ipsec  get_x509  rfc3948.txt  rfc4303.txt
[rfcs]$./clean_em 
[rfcs]$ls
clean_em  get_ipsec  get_x509
```
