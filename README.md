# Snowflake-Linux-Build

***Building latest Snowflake on Linux***

```
apt update
apt upgrade
apt install build-essential golang-go git
git clone https://gitlab.torproject.org/tpo/anti-censorship/pluggable-transports/snowflake.git
cd snowflake/proxy
go build
./proxy
```
