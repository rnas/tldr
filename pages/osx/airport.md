<<<<<<< HEAD
# Airport

> Airport utility

- Create a symlink so you can easily run 'airport' without specifying a path.

`sudo ln -s /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport /usr/sbin/airport`

- Scan for available wireless networks

`airport -s`

- Disassociate from current airport network
=======
# airport

> Wireless network configuration utility.

- Show current wireless status information:

`airport -I`

- Sniff wireless traffic on channel 1:

`airport sniff {{1}}`

- Scan for available wireless networks:

`airport -s`

- Disassociate from current airport network:
>>>>>>> upstream/master

`sudo airport -z`
