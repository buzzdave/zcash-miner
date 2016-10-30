# zog_zcash-miner
a binary that works in 14.04 under ethOS w/AMD gpus (Hawaii, Tahiti, Tonga)  haven't tested with much else yet
I don't run any nVidia GPUs with this, so I don't know if that works

This was an early intermediate build - Your mileage may vary!

I run this against a pool like so:
./zcash-miner -printtoconsole -stratum=stratum+tcp://us1-zcash.flypool.org:3333 -user=<zecpaymentaddress>.gpu_23_3 -password=z -G -S=0

Note: S=0 specifies GPU 0, so run one instance per GPU and change each command line.
