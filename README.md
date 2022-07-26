# Nat Peterson's personal PiKVM ansible script

Edit `home` with your pikvm IP addresses and what the static IP's should be.

Edit `packages.yml` to use your `remote_jack_trip_server`

Setup your PiVKM with Jack and JackTrip 

```shell
ansible-playbook  packages.yml
```

Restart Jack & JackTrip clients

```shell
ansible-playbook  restart-jack.yml
```
