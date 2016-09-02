TvE's notes
===========

- build using `docker build -t docker-mosquitto .`
- create ./data and /var/log/mosquitto
- added voneicken.com to config/conf.d
- link unit file to /etc/systemd/system/docker-mosquitto.service
- `systemctl daemon-reload` `systemctl enable docker-mosquitto.service`
  `systemctl start docker-mosquitto.service`


