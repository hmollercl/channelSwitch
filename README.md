# channelSwitch
channel switcher to replicate guitar amp channel switch

to build:

gcc -fvisibility=hidden -fPIC -Wl,-Bstatic -Wl,-Bdynamic -Wl,--as-needed -shared -pthread `pkg-config --cflags lv2` -lm `pkg-config --libs lv2` channelSwitch.c -o channel
