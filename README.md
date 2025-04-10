# qperf-vsock

qperf支持vsock通道

客户端
`qperf 4 --vsock -oo msg_size:4K:64K:*2 -vu vsock_bw`

服务端
`qperf --vsock`

Output
```
vsock_bw:
    bw        =  283 KB/sec
    msg_size  =    1 bytes
vsock_bw:
    bw        =  562 KB/sec
    msg_size  =    2 bytes
vsock_bw:
    bw        =  1.17 MB/sec
    msg_size  =     4 bytes
vsock_bw:
    bw        =  2.12 MB/sec
    msg_size  =     8 bytes
vsock_bw:
    bw        =  3.91 MB/sec
    msg_size  =    16 bytes
vsock_bw:
    bw        =  7.71 MB/sec
    msg_size  =    32 bytes
vsock_bw:
    bw        =  15 MB/sec
    msg_size  =  64 bytes
vsock_bw:
    bw        =  30.2 MB/sec
    msg_size  =   128 bytes
vsock_bw:
    bw        =  61.1 MB/sec
    msg_size  =   256 bytes
vsock_bw:
    bw        =  117 MB/sec
    msg_size  =  512 bytes
vsock_bw:
    bw        =  218 MB/sec
    msg_size  =    1 KiB (1,024)
vsock_bw:
    bw        =  420 MB/sec
    msg_size  =    2 KiB (2,048)
vsock_bw:
    bw        =  768 MB/sec
    msg_size  =    4 KiB (4,096)
vsock_bw:
    bw        =  1.31 GB/sec
    msg_size  =     8 KiB (8,192)
vsock_bw:
    bw        =  1.72 GB/sec
    msg_size  =    16 KiB (16,384)
vsock_bw:
    bw        =  2.05 GB/sec
    msg_size  =    32 KiB (32,768)
vsock_bw:
    bw        =  2.07 GB/sec
    msg_size  =    64 KiB (65,536)

```
